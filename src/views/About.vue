<template>
  <div id="about">
    <section>
      <shared-header pageTitle="About Us" headerImage="image11.jpg" />
    </section>
    <section class="uk-margin-large">
      <div class="uk-container uk-padding-large">
        <div class="uk-child-width-1-2@s" uk-grid>
          <div>
            <h3 class="uk-h1 uk-text-light">Company's Overview</h3>
            <h5 class="uk-h5 uk-text-light">Our mission is to help enterprises accelerate adoption of new technologies, untangle complex issues that always emerge during digital evolution, and orchestrate ongoing innovation. 
            <br/><br/>
            Whether it is a consumer-oriented app or a transformative enterprise-class solution, the company leads the process from ideation and concept to delivery, and provides ongoing support</h5>
          </div>
          
          <div>
            <img src="../assets/images/image6.jpg" alt="">
          </div>
        </div>
      </div>
    </section>

    <solution />
  </div>
</template>

<script>
import SharedHeader from '../components/SharedHeader.vue'
import Solution from '../components/Solution.vue'

export default {
  name: 'About',
  components: {
    SharedHeader,
    Solution
  }
}
</script>

<style lang="less" scoped>
  #team {
    img {
      width: 250px;
      margin-bottom: 1rem;
    }
  }

  .border-left {
      border-left: 1px solid #ddd !important;
  }

  .border-bottom {
    border-bottom: 1px solid #ddd;
  }
</style>