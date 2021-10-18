<template>
  <div id="services">
    <shared-header pageTitle="Services" headerImage="image3.jpg" />

    <section>
      <div class="uk-container uk-padding-large">
        <div class="uk-text-center">
          <h2 class="uk-h1 uk-text-light">Services we offer</h2>
          <img src="../assets/images/line1.jpeg" alt="" class="mx-auto">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid>
          <div>
            <img src="../assets/images/image6.jpg" alt="">
          </div>
          <div>
            <h3 class="uk-h1 uk-text-light">Web Development</h3>
            <h5 class="uk-h5 uk-text-light">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam, ad quos omnis tenetur facilis sit repellat dolores dignissimos alias enim dicta? Consequatur fugit illo eligendi ducimus minima nisi ratione cupiditate. Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident est dolore laboriosam atque amet, maxime possimus accusamus odit libero minima quas distinctio, autem nostrum necessitatibus, voluptates corrupti mollitia quasi minus!</h5>
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line2.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid>
          <div>
            <h3 class="uk-h1 uk-text-light">App Development</h3>
            <h5 class="uk-h5 uk-text-light">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam, ad quos omnis tenetur facilis sit repellat dolores dignissimos alias enim dicta? Consequatur fugit illo eligendi ducimus minima nisi ratione cupiditate. Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident est dolore laboriosam atque amet, maxime possimus accusamus odit libero minima quas distinctio, autem nostrum necessitatibus, voluptates corrupti mollitia quasi minus!</h5>
          </div>
          <div>
            <img src="../assets/images/mobile.jpeg" alt="">
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line3.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid>
          <div>
            <img src="../assets/images/cloud.jpeg" alt="">
          </div>
          <div>
            <h3 class="uk-h1 uk-text-light">Cloud Maintenance</h3>
            <h5 class="uk-h5 uk-text-light">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam, ad quos omnis tenetur facilis sit repellat dolores dignissimos alias enim dicta? Consequatur fugit illo eligendi ducimus minima nisi ratione cupiditate. Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident est dolore laboriosam atque amet, maxime possimus accusamus odit libero minima quas distinctio, autem nostrum necessitatibus, voluptates corrupti mollitia quasi minus!</h5>
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line2.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid>
          <div>
            <h3 class="uk-h1 uk-text-light">UX/UI Design</h3>
            <h5 class="uk-h5 uk-text-light">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam, ad quos omnis tenetur facilis sit repellat dolores dignissimos alias enim dicta? Consequatur fugit illo eligendi ducimus minima nisi ratione cupiditate. Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident est dolore laboriosam atque amet, maxime possimus accusamus odit libero minima quas distinctio, autem nostrum necessitatibus, voluptates corrupti mollitia quasi minus!</h5>
          </div>
          <div>
            <img src="../assets/images/uxdesign.jpeg" alt="">
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line3.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid>
          <div>
            <img src="../assets/images/itconsultant.jpeg" alt="">
          </div>
          <div>
            <h3 class="uk-h1 uk-text-light">IT Consulting</h3>
            <h5 class="uk-h5 uk-text-light">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam, ad quos omnis tenetur facilis sit repellat dolores dignissimos alias enim dicta? Consequatur fugit illo eligendi ducimus minima nisi ratione cupiditate. Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident est dolore laboriosam atque amet, maxime possimus accusamus odit libero minima quas distinctio, autem nostrum necessitatibus, voluptates corrupti mollitia quasi minus!</h5>
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line2.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid>
          <div>
            <h3 class="uk-h1 uk-text-light">Enterprise Software Development</h3>
            <h5 class="uk-h5 uk-text-light">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam, ad quos omnis tenetur facilis sit repellat dolores dignissimos alias enim dicta? Consequatur fugit illo eligendi ducimus minima nisi ratione cupiditate. Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident est dolore laboriosam atque amet, maxime possimus accusamus odit libero minima quas distinctio, autem nostrum necessitatibus, voluptates corrupti mollitia quasi minus!</h5>
          </div>
          <div>
            <img src="../assets/images/enterprise.png" alt="">
          </div>
        </div>
      </div>
    </section>
    <solution/>
  </div>
</template>

<script>
import SharedHeader from '../components/SharedHeader.vue'
import Solution from '../components/Solution.vue'

export default {
  name: 'Services',
  components: {
    SharedHeader,
    Solution
  }
}
</script>

<style>

</style>