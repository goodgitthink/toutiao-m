<template>
  <div id="app">
    <h1>黑马头条</h1>
    <i class="iconfont icon-lishi"></i>
    <van-button type="info">信息按钮</van-button>
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped lang="less"></style>
