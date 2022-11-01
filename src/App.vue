<template>
  <div id="app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {}
}
</script>

<style>
#app {
  margin: 0;
  padding: 0;
  height: 100%;
}
/* 取消全局滚动条 */
::-webkit-scrollbar {
  display: none;
}
</style>
