<template>
  <div id="contact">
    <shared-header pageTitle="Contact Us" headerImage="image8.jpg" />

    <section class="uk-section uk-margin-remove-bottom uk-padding-remove-bottom">
      <div class="uk-container uk-padding-large uk-padding-remove-bottom">
        <div class="uk-child-width-1-2@s" uk-grid>
          <div>
            <img src="../assets/images/image4.jpg" alt="">
          </div>
          <div class="uk-padding">
            <h2 class="uk-h1 uk-text-light">Want to work with us?</h2>
            <h5 class="uk-h4 uk-text-light uk-margin-small">
              You can contact us to talk more on your projects. We will respond to you in less than 24 hours.
            </h5>
            <a href="#contact-form" class="uk-button uk-button-primary uk-margin uk-button-rounded">Scroll Down</a>
          </div>
        </div>
      </div>
    </section>

    <div class="uk-text-center uk-margin">
      <img src="../assets/images/line1.jpeg" alt="">
    </div>

    <section id="contact-form">
      <div class="uk-container uk-padding-large uk-padding-remove-top">
        <h2 class="uk-h1 uk-text-light uk-text-center">Let’s talk about everything!</h2>
        <div class="container-sm">
          <form class="uk-form-stacked" @submit.prevent="sendMessage">
            <div class="uk-grid-small uk-grid">
              <div class="uk-width-1-3@s mb-3">
                <label class="uk-form-label">Name</label>
                <input class="uk-input input-rounded" type="email" placeholder="John Doe">
              </div>
              <div class="uk-width-1-3@s mb-3">
                <label class="uk-form-label">Email</label>
                <input class="uk-input input-rounded" type="email" placeholder="johndoe@email.com">
              </div>
              <div class="uk-width-1-3@s mb-3">
                <label class="uk-form-label">Phone</label>
                <input class="uk-input input-rounded" type="number" placeholder="+234-9012345678">
              </div>
              <div class="uk-width-1-1 uk-margin-small">
                <label class="uk-form-label">Message</label>
                <textarea class="uk-textarea input-rounded" rows="5" placeholder="Your message"></textarea>
              </div>
            </div>
            <button class="uk-button uk-button-primary uk-button-rounded uk-text-center uk-margin" type="submit">Submit message</button>
          </form>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import SharedHeader from '../components/SharedHeader.vue'
import UIkit from 'uikit'

export default {
  name: 'Contact',
  components: {
    SharedHeader
  },
  methods: {
    sendMessage() {
      UIkit.notification({message:'<span uk-icon=\'icon: check\'></span> Message sent', pos: 'top-right'}, {status:'success'})
    }
  }
}
</script>

<style>

</style>