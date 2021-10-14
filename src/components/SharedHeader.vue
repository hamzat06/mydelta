<template>
  <div class="header-container">
    <img src="../assets/images/dummy1.jpeg" alt="">
    <div class="uk-text-center">
      <h1 class="text-white uk-h1 uk-text-light">{{ pageTitle }}</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SharedHeader',
  props: {
    pageTitle: String
  }
}
</script>

<style lang="less" scoped>
.header-container {
  width: 100%;
  overflow: hidden;

  img {
    width: 100%;
    max-height: 400px;
  }
}

h1 {
  position: relative;
  bottom: 200px;
  @media only screen and (max-width: 1024px) {
    bottom: 200px;
  }

  @media only screen and (max-width: 600px) {
    bottom: 90px;
  }

  @media only screen and (max-width: 400) {
    bottom: 45px;
  }
}
</style>