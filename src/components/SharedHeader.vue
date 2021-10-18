<template>
  <div class="header-container uk-cover-container">
    <img :src="require(`../assets/images/${headerImage}`)" alt="" uk-cover>
    <div class="uk-overlay-primary uk-position-cover"></div>
    <section class="uk-section" id="about-header">
    </section>
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
  bottom: 70px;
  @media only screen and (max-width: 1024px) {
    bottom: 50px;
  }

  @media only screen and (max-width: 959px) {
    bottom: 30px;
  }
}
</style>