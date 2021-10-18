<template>
  <div class="header-container uk-padding-large uk-cover-container">
    <img :src="require(`../assets/images/${headerImage}`)" alt="" uk-cover>
    <div class="uk-overlay-primary uk-position-cover"></div>
    <div class="uk-text-center uk-padding-large">
      <h1 class="text-white uk-h1 uk-text-light">{{ pageTitle }}</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SharedHeader',
  props: {
    pageTitle: String,
    headerImage: String
  }
}
</script>

<style lang="less" scoped>
.header-container {
  width: 100%;
  overflow: hidden;
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