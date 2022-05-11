<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Header from './views/components/Header.vue'
import Content from './views/components/Content.vue'
import Footer from './views/components/Footer.vue'
</script>

<template>
  <Header></Header>
  <Content></Content>
  <Footer></Footer>
</template>

<style>
@import './style/css/reset.css';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  /* color: #2c3e50; */
  /* margin-top: 60px; */
}
</style>
