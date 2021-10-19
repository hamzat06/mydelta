<template>
  <div id="clients">
    <shared-header pageTitle="Our Clients" headerImage="image7.jpg" />
    <section class="uk-section-muted">
      <div class="uk-container uk-padding-large">
        <div uk-filter="target: .js-filter">

            <ul class="uk-subnav uk-subnav-pill">
                <li class="uk-active" uk-filter-control><a href="#">All</a></li>
                <!-- <li uk-filter-control="[data-category='white']"><a href="#">White</a></li>
                <li uk-filter-control="[data-category='blue']"><a href="#">Blue</a></li>
                <li uk-filter-control="[data-category='black']"><a href="#">Black</a></li> -->
            </ul>

            <ul class="js-filter uk-child-width-1-2 uk-text-center" uk-grid="masonry: true">
                <li v-for="client in clients" :key="client.index" :data-category="client.category">
                    <div class="uk-inline-clip uk-transition-toggle" tabindex="0">
                        <img :src="require(`../assets/images/${client.image}`)" alt="">
                        <div class="uk-transition-fade uk-position-cover uk-position-small uk-overlay uk-overlay-primary uk-flex uk-flex-center uk-flex-middle">
                            <div class="uk-text-center">
                                <div class="uk-transition-slide-top-small"><h4 class="uk-margin-remove">{{ client.name }}</h4></div>
                                <div class="uk-transition-slide-bottom-small uk-margin">
                                    <a class="uk-button uk-button-primary" :href="client.link">Go to platform</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </li>
            </ul>

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
  name: 'Clients',
  components: {
    SharedHeader,
    Solution
  },
  data: () => ({
      clients: [
          {
              name: 'Bitwire Limited',
              link: 'bitwire.ltd',
              image: 'job1.png'
          },
          {
              name: 'Zenith',
              link: 'financezenith.com',
              image: 'job2.png'
              
          }
      ]
  })
}
</script>

<style lang="less" scoped>
</style>