<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
  #app {
    width: 100vw;
    height: 100vh;
    font-size: 12px;  /* 全局默认字体大小 */
  }
</style>
