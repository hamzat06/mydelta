<template>
  <div id="contact">
    <shared-header pageTitle="Contact Us" />

    <section class="uk-section">
      <div class="uk-container uk-padding-large">
        <div class="uk-child-width-1-2@s" uk-grid>
          <div>
            <img src="../assets/images/dummy1.jpeg" alt="">
          </div>
          <div class="uk-padding">
            <h2 class="uk-h1 uk-text-light">Want to work with us?</h2>
            <h5 class="uk-h4 uk-text-light uk-margin-small">
              Do you want to personally try out the VR? Find out where you can experience the headset and games for  VR near you.
            </h5>
          </div>
        </div>
      </div>
    </section>

    <section class="uk-section">
      <div class="uk-container">
        <h2 class="uk-h1 uk-text-light uk-text-center">Let’s talk about everything!</h2>
        <div class="container-sm">
          <form class="uk-form-stacked" @submit.prevent>
            <div class="uk-grid-small uk-grid">
              <div class="uk-width-1-3@s uk-margin-small">
                <label class="uk-form-label">Name</label>
                <input class="uk-input input-rounded" type="text" placeholder="John Doe">
              </div>
              <div class="uk-width-1-3@s uk-margin-small">
                <label class="uk-form-label">Email</label>
                <input class="uk-input input-rounded" type="email" placeholder="johndoe@email.com">
              </div>
              <div class="uk-width-1-3@s uk-margin-small">
                <label class="uk-form-label">Phone</label>
                <input class="uk-input input-rounded" type="number" placeholder="+234-9012345678">
              </div>
              <div class="uk-width-1-1 uk-margin-small">
                <label class="uk-form-label">Message</label>
                <textarea class="uk-textarea input-rounded" rows="5" placeholder="Your message"></textarea>
              </div>
            </div>
            <button class="uk-button uk-button-primary uk-button-rounded uk-text-center uk-margin" type="submit">Submit comment</button>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import SharedHeader from '../components/SharedHeader.vue'

export default {
  name: 'Contact',
  components: {
    SharedHeader
  }
}
</script>

<style>

</style>