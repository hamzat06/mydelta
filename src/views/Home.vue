<template>
  <div id="home">
    <section class="uk-position-relative uk-visible-toggle uk-light" tabindex="-1" uk-slideshow="autoplay: true; min-height: 300; max-height: 600; animation: push">

        <ul class="uk-slideshow-items">
            <li>
                <img src="../assets/images/image6.jpg" alt="" uk-cover>
                <div class="uk-overlay-primary uk-position-cover"></div>
                <div class="uk-position-center uk-text-center">

                    <h2 uk-slider-parallax="x: 100,-100">WELCOME TO MY-DELTA</h2>
                    <p uk-slider-parallax="x: 200,-200" class="text-white">A Multi-faceted Technology solution Company</p>
                    <div>
                      <router-link to="/about" class="uk-button uk-button-primary uk-button-rounded">Learn more</router-link>
                    </div>

                </div>
            </li>
            <li>
                <img src="../assets/images/image10.jpg" alt="" uk-cover>
                <div class="uk-overlay-primary uk-position-cover"></div>
                <div class="uk-position-center uk-text-center">
                    <h2 uk-slider-parallax="x: 100,-100"> ENTERPRISE SOFTWARE DEVELOPMENT</h2>
                    <p uk-slider-parallax="x: 200,-200" class="text-white"> Leverage our expertise to create a solid software foundation for your business. </p>
                    <div>
                      <router-link to="/services" class="uk-button uk-button-primary uk-button-rounded">Learn more</router-link>
                    </div>
                </div>
            </li>
            <li>
                <img src="../assets/images/image5.jpg" alt="" uk-cover>
                <div class="uk-overlay-primary uk-position-cover"></div>
                <div class="uk-position-center uk-text-center">

                    <h2 uk-slider-parallax="x: 100,-100">WORLD CLASS CREATIVE DIGITAL EXPERIENCE</h2>
                    <p uk-slider-parallax="x: 200,-200" class="text-white">We push the boundaries of Software development.</p>
                    <div>
                      <router-link to="/about" class="uk-button uk-button-primary uk-button-rounded">Learn more</router-link>
                    </div>

                </div>
            </li>
        </ul>

    </section>
    <section class="uk-section uk-margin-large">
      <div class="uk-container">
        <div class="uk-text-center">
          <h2 class="uk-h1 uk-text-light">Stress-free solution for your business</h2>
          <img src="../assets/images/line1.jpeg" alt="" class="mx-auto">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid>
          <div>
            <img src="../assets/images/image2.jpg" alt="">
          </div>
          <div>
            <h3 class="uk-h1 uk-text-light">Perfect for any business large and small</h3>
            <h5 class="uk-h5 uk-text-light">We are a digital transformation consultancy and software development company that provides cutting edge solutions.</h5>
            <router-link to="/services" class="uk-button uk-button-outlined-primary uk-button-rounded uk-text-semibold uk-margin">How it works?</router-link>
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line2.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid>
          <div>
            <h3 class="uk-h1 uk-text-light">Business management is now a brand experience</h3>
            <h5 class="uk-h5 uk-text-light">Scale your delivery capacity with intelligent dedicated developers.</h5>
            <router-link to="/about" class="uk-button uk-button-outlined-primary uk-button-rounded uk-text-semibold uk-margin">Learn more</router-link>
          </div>
          <div>
            <img src="../assets/images/image3.jpg" alt="">
          </div>
        </div>

        <div class="uk-text-center">
          <img src="../assets/images/line3.jpeg" alt="">
        </div>
        <div class="uk-child-width-1-2@s uk-padding" uk-grid>
          <div>
            <img src="../assets/images/image11.jpg" alt="">
          </div>
          <div>
            <h3 class="uk-h1 uk-text-light">We take care of all details, you get it all covered</h3>
            <h5 class="uk-h5 uk-text-light">A dedicated, customized, and secure Team Extension model follows our client's internal development practices, methodologies, and culture.</h5>
            <router-link to="/about" class="uk-button uk-button-outlined-primary uk-button-rounded uk-text-semibold uk-margin">Learn more</router-link>
          </div>
        </div>
      </div>
    </section>

    <section class="uk-section uk-section-muted uk-padding-large">
      <div class="uk-container uk-padding-large">
        <div class="container-sm uk-text-center">
          <h2 class="uk-h1 uk-text-light">Smarter decisions, better business</h2>
        </div>
      
        <div class="uk-child-width-1-1 uk-child-width-1-2@s uk-margin-large" uk-grid>
          <div class="uk-margin g1">
            <img src="../assets/images/g5.png" alt="">
            <h4 class="uk-h4 uk-text-light">Enterprise Software Development</h4>
            <p class="uk-text-light">Create complex enterprise software, ensure reliable software integration, modernise your legacy system.</p>
          </div>
          <div>
            <img src="../assets/images/g4.png" alt="">
            <h4 class="uk-h4 uk-text-light">Dedicated Development Team</h4>
            <p class="uk-text-light">Hire a loyal software development team with niche skills and deep expertise.</p>
          </div>
          <div>
            <img src="../assets/images/g6.png" alt="">
            <h4 class="uk-h4 uk-text-light">IT Consulting</h4>
            <p class="uk-text-light">Trust our top minds to eliminate workflow pain points, implement new tech, and consolidate app portfolios.</p>
          </div>

          <div>
            <img src="../assets/images/g1.png" alt="">
            <h4 class="uk-h4 uk-text-light">UX / UI Design</h4>
            <p class="uk-text-light">Build the product you need on time with an experienced team that uses a clear and effective design process.</p>
          </div>

        </div>
      </div>
    </section>
  </div>
</template>

<script>

export default {
  name: 'Home'
}
</script>
