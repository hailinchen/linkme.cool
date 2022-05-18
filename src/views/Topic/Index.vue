<script setup lang="ts">
import topicList from '../../data/json/topicList.json'
console.log('topicList:', topicList)
</script>

<template>
    <div class="topic-wrapper">
        <!-- <a target="_blank" href="https://www.douyin.com">
            <div class="topic">
                <img class="icon icon-topic" src="./assets/images/logo/douyin-logo-horizontal-small.svg" alt="抖音" />
            </div>
        </a> -->
        <!-- <a target="_blank" href="https://www.ixigua.com/">
            <div class="topic">
                <img class="icon icon-topic" src="./assets/images/logo/xigua-logo.svg" alt="西瓜视频"/>
            </div>
        </a> -->
        
        <!-- <div class="topic" v-for="(item, index) in topicList" :key="index">
            <a target="_blank" href="https://doyoudo.com/">
                <img class="icon icon-topic" src="../../assets/image/logo/doyoudo-logo.png" alt="doyoudo.com" />
            </a>
        </div> -->

        <div class="topic" v-for="(item, index) in topicList" :key="index">
            <a target="_blank" :href="item.topicUrl"><img class="icon icon-topic" :src="item.logoUrl" :alt="item.topicName" /></a>
        </div>
    </div>
</template>

<style scoped>
.mark-wrapper h3 {
    color: rgb(240, 77, 77);
    /* color: rgb(82, 137, 240); */
}
.mark-wrapper a {
    margin-bottom: 12px;
    display: inline-block;
}
</style>