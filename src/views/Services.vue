<template>
  <div id="services">
    <shared-header pageTitle="Services" headerImage="image3.jpg" />

    <section>
      <div class="uk-container uk-padding-large">

        <div class="uk-text-center">
          <h2 class="uk-h1 uk-text-light">Services we offer</h2>
          <img src="../assets/images/line1.jpeg" alt="" class="mx-auto">
        </div>
        
        <div class="uk-child-width-1-2@s uk-padding" uk-grid id="ux-ui">
          <div>
            <h3 class="uk-h1 uk-text-light">UX/UI Design</h3>
            <h5 class="uk-h4 uk-text-light">
              Our skillful engineers create interactive prototyping and usability testing to ensure a project with a pleasant user experience. That means your users get good enough experience that enable them to engage and interact on your website and/or mobile app.
            </h5>
          </div>
          <div>
            <img src="../assets/images/uxdesign.jpeg" alt="">
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line3.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid id="web">
          <div>
            <img src="../assets/images/image6.jpg" alt="">
          </div>
          <div>
            <h3 class="uk-h1 uk-text-light">Web Development</h3>
            <h5 class="uk-h4 uk-text-light">
              We ideate and plan to design and develop custom web solutions to connect our clients with their customers efficiently. Let’s develop feature-rich, highly functional, robust, secure, and scalable custom web solutions along with engaging UI/UX design that enhances your brand.
            </h5>
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line2.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid id="mobile">
          <div>
            <h3 class="uk-h1 uk-text-light">App Development</h3>
            <h5 class="uk-h4 uk-text-light">
              Our skillful engineers actively build quality hybrid mobile apps and APIs that seamlessly integrate with third-party mobile applications. Our team uses React-Native to build interactive cross-platform mobile applications.
            </h5>
          </div>
          <div>
            <img src="../assets/images/mobile.jpeg" alt="">
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line3.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid id="it-consulting">
          <div>
            <img src="../assets/images/itconsultant.jpeg" alt="">
          </div>
          <div>
            <h3 class="uk-h1 uk-text-light">IT Consulting</h3>
            <h5 class="uk-h4 uk-text-light">
              Our team of skilled IT consultants will help your business grow via analyzing and diagnosing your IT infrastructure, understanding your business needs, and designing and implementing a technology solution.
            </h5>
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line2.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid id="enterprise">
          <div>
            <h3 class="uk-h1 uk-text-light">Enterprise Software Development</h3>
            <h5 class="uk-h4 uk-text-light">
              Leverage our technical expertise and industry-specific knowledge to scale and automate your business processes. My-Delta offers a full spectrum of enterprise web application / mobile application development. Our enterprise app developers help you develop, design, and implement omnichannel enterprise solutions.
            </h5>
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