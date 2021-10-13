<template>
  <div id="page-loader">
    <div class="cube"></div>
    <div class="cube"></div>
    <div class="cube"></div>
    <div class="cube"></div>
  </div>
</template>

<script>
export default {
  name: 'PageLoader'
}
</script>

<style lang="less" scoped>
@import "for";
@colors: #EE4F39, #333333, #EC4152, #111111;
.page-loader {
  display: flex;
  justify-content: center;
  align-items: center;
  position: fixed;
  top: 0;
  width: 100vw;
  height: 100vh;
  background-color: #eee;
  z-index: 1000;

  .cube {
    width: 40px;
    height: 40px;
    margin-right: 10px;

      
  }
}
</style>