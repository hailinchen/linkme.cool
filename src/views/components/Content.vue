<script setup lang="ts">
import topicList from '../../data/json/topicList.json'
console.log('topicList:', topicList)
</script>

<template>
    <section class="content frame">
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
        <div class="mark-wrapper"></div>
    </section>
</template>

<style scoped>
.content {
    max-width: 800px;
    margin: 10px auto;
    padding: 40px 20px;
    /* height: 80vh; */
    /* height: 1000px; */
    /* height: calc(100vh - 224px); */
    /* height: calc(100vh - 234px); */
    /* overflow: scroll; */
    min-height: 100vh;
}

.mark-wrapper h3 {
    color: rgb(240, 77, 77);
    /* color: rgb(82, 137, 240); */
}
.mark-wrapper a {
    margin-bottom: 12px;
    display: inline-block;
}
</style>