<script lang="ts">
export default {
  props: {
    url: String
  },
  setup(props) {
    console.log('props.url:', props.url)
  }
}
</script>



<template>
    <div class="mobile-browser-wrapper">
        <!-- <iframe src="https://m.youtube.com/" frameborder="0" width="375" height="667"></iframe> -->
        <iframe :src="url" frameborder="0" width="1080" height="750"></iframe>
    </div>
</template>

<style scoped>
.mobile-browser-wrapper {
    width: 1080px;
    /* height: 667px; */
    height: 750px;
    box-shadow: 2px 2px 2px #e2e2e2;
}
.mobile-browser-wrapper iframe {
    height: 100%;
}
</style>