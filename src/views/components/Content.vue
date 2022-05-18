<script setup lang="ts">
import MobileBrowser from './MobileBrowser.vue'
import PCBrowser from './PCBrowser.vue'
// import Topic from '../Topic/Index.vue'
</script>

<template>
    <section class="content flex">
        <!-- <PCBrowser class="item" url="https://www.mgtv.com/"/> -->
        <!-- <PCBrowser class="item" url="https://v.qq.com/"/> -->
        <!-- <PCBrowser class="item" url="https://y.qq.com/"/> -->
        <!-- <PCBrowser class="item" url="https://www.ixigua.com/"/> -->
        <PCBrowser class="item" url="https://www.douyin.com/"/>
        <!-- 薛汀哲 抖音 -->
        <PCBrowser class="item" url="https://www.douyin.com/user/MS4wLjABAAAA-x7GM0_Fcxel8a2wyt_tzTw_yo5198XFQIqW9BihLgg"/>
        <PCBrowser class="item" url="https://www.youku.com/"/>
        <PCBrowser class="item" url="https://www.youtube.com/"/>
        
        <!-- <MobileBrowser class="item" url="https://m.youtube.com/"/> -->
        <!-- <MobileBrowser class="item" url="https://www.netflix.com/hk/browse/genre/839338"/> -->
        <!-- <MobileBrowser class="item" url="https://naifei.pro/m/"/> -->

        <!-- <MobileBrowser class="item" url="https://m.bilibili.com/space/29959830"/> -->
        <!-- <MobileBrowser class="item" url="https://m.mgtv.com/"/> -->
        <!-- <MobileBrowser class="item" url="https://m.twitch.tv/"/> -->
        <!-- <MobileBrowser class="item" url="https://www.tiktok.com/"/> -->
        <!-- <MobileBrowser class="item" url="https://www.iq.com/"/> -->
        <!-- <MobileBrowser class="item" url="https://m.bilibili.com/"/> -->
        <!-- <MobileBrowser class="item" url="https://m.v.qq.com/"/> -->
        <!-- <MobileBrowser class="item" url="https://m.ixigua.com/"/> -->
        <!-- <MobileBrowser class="item" url="https://m.weibo.cn/"/> -->
        <!-- <MobileBrowser class="item" url="https://ddrk.me/"/> -->
        <!-- <MobileBrowser class="item" url="https://www.nftcn.com.cn/h5/#/"/> -->
        <!-- <MobileBrowser class="item" url="https://linktr.ee/allenchan"/> -->
        
    </section>
</template>

<style scoped>
.content {
    /* max-width: 800px; */
    margin: 10px auto;
    /* padding: 40px 20px; */
    /* height: 80vh; */
    /* height: 1000px; */
    /* height: calc(100vh - 224px); */
    /* height: calc(100vh - 234px); */
    /* overflow: scroll; */
    /* min-height: 100vh; */
}
.grid {
    display: grid;
    gap: 50px;
    grid-template-columns: auto auto auto auto;
}

.flex {
    display: flex;
    /* align-items: center; */
    justify-content: center;
    flex-wrap: wrap;
}
.flex .item {
    margin: 25px;
}
</style>