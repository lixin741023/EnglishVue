<template>
  <div class="app">
    12345600
    <input type="text" />
    <router-view></router-view>
  </div>
</template>

<script>
  export default {
    name: "app"
  }
</script>

<style scoped lang="less">
  .app{
    border: 1px solid #ccc;
    padding: 5px;
  }
</style>
