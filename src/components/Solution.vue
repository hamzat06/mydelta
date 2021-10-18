<template>
  <section class="uk-section uk-section-primary uk-margin-remove-top" id="solution">
  <div class="uk-container">
    <div class="uk-grid-collapse uk-child-width-expand@s uk-padding uk-padding-remove-top uk-padding-remove-bottom" uk-grid>
        <div id="contact-us-text">
            <h3>GET SOLUTION TO YOUR PROBLEMS</h3>
            <p class="text-white">You can contact us to talk more on your projects</p>
        </div>
        <div class="uk-text-right" id="contact-us-btn">
            <router-link to="/contact" class="uk-button uk-button-rounded">Contact Us</router-link>
        </div>
    </div>
  </div>
</section>
</template>

<script>
export default {
  name: 'Solution'
}
</script>

<style lang="less" scoped>
a {
  color: #fff;
  border: 1px solid #fff;
  &:hover {
    background: #fff;
    color: #EE4F39 !important;
    transition: .5s ease-in-out;
  }
}
</style>