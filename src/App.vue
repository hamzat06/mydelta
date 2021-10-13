<template>
  <div id="app">
    <div class="uk-preserve-color">

        <div uk-sticky="animation: uk-animation-slide-top; sel-target: .navbar; cls-active: uk-background-secondary uk-navbar-sticky uk-box-shadow-small; cls-inactive: uk-navbar-transparent uk-light uk-position-fixed; top: 200">

            <nav class="navbar">
                <div class="uk-container uk-container-expand">
                    <div uk-navbar>
                      <div class="uk-navbar-left">
                        <router-link to="/" class="uk-navbar-item uk-logo uk-text-bold uk-light">MyDelta</router-link>
                      </div>
                      <div class="uk-navbar-right">
                        <ul class="uk-navbar-nav uk-text-semibold">
                            <li><router-link to="/" active-class="uk-active">Home</router-link></li>
                            <li><router-link to="/about">About Us</router-link></li>
                            <li><router-link to="/services">Services</router-link></li>
                            <li><router-link to="/clients">Clients</router-link></li>
                            <li><router-link to="/contact">Contact Us</router-link></li>
                        </ul>
                      </div>

                    </div>
                </div>
            </nav>
        </div>

        <router-view/>

        <footer class="uk-section uk-section-secondary uk-padding-large uk-padding-remove-bottom">
          <div class="uk-container">
            <div class="uk-child-width-1-1 uk-child-width-1-2@s uk-child-width-1-4@m" uk-grid>
              <div>
                <router-link to="/" class="uk-logo uk-text-bold uk-light uk-h3">MyDelta</router-link>
              </div>
              <div>
                <h3 class="uk-h4 uk-text">Product</h3>
                <ul class="uk-list">
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">About App</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Jobs</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Contact Us</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Legal</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Help and support</a>
                  </li>
                </ul>
              </div>
              <div>
                <h3 class="uk-h4">Company</h3>
                <ul class="uk-list">
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">About Us</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Features</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Technology</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Store</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Help and support</a>
                  </li>
                </ul>
              </div>
              <div>
                <h3 class="uk-h4">Social</h3>
                <ul class="uk-list">
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Twitter</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Instagram</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Facebook</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Youtube</a>
                  </li>
                  <li>
                    <a href="" class="uk-text-light uk-button uk-button-link">Pinterest</a>
                  </li>
                </ul>
              </div>
            </div>
            <hr>
            <div class="uk-flex uk-flex-between">
              <p>My Delta &copy; 2021 / All Rights Reserved</p>
              <div>
                <a href="" uk-icon="icon: facebook" class="uk-margin-small-right"></a>
                <a href="" uk-icon="icon: google" class="uk-margin-small-right"></a>
                <a href="" uk-icon="icon: instagram" class="uk-margin-small-right"></a>
                <a href="" uk-icon="icon: twitter" class="uk-margin-small-right"></a>
                <a href="" uk-icon="icon: youtube" class="uk-margin-small-right"></a>
              </div>
            </div>
          </div>
        </footer>

    </div>

  </div>
</template>

<script>

export default {
  components: {  } 
}
</script>


<style lang="less">
#app {
  // font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

nav {
  z-index: 999;
  width: 100%;
  a {
    &.router-link-exact-active {
      opacity: 1;
      color: #fff !important;
    }
  }
}

footer {
  color: #D3D4D4 !important;
}

// #nav {
//   padding: 30px;

//   a {
//     font-weight: bold;
//     color: #2c3e50;

//     &.router-link-exact-active {
//       color: #42b983;
//     }
//   }
// }
</style>
