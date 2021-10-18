<template>
  <div id="clients">
    <shared-header pageTitle="Our Clients" headerImage="image7.jpg" />
    <section>
      <div class="uk-container uk-padding-large">
        <div uk-filter="target: .js-filter">

            <ul class="uk-subnav uk-subnav-pill">
                <li class="uk-active" uk-filter-control><a href="#">All</a></li>
                <li uk-filter-control="[data-category='white']"><a href="#">White</a></li>
                <li uk-filter-control="[data-category='blue']"><a href="#">Blue</a></li>
                <li uk-filter-control="[data-category='black']"><a href="#">Black</a></li>
            </ul>

            <ul class="js-filter uk-child-width-1-2 uk-child-width-1-3@m uk-child-width-1-4@l uk-text-center" uk-grid="masonry: true">
                <li v-for="client in clients" :key="client.index" :data-category="client.category">
                    <h6>Category: {{client.category}}</h6>
                    <div class="uk-inline-clip uk-transition-toggle" tabindex="0">
                        <img src="../assets/images/dummy1.jpeg" alt="">
                        <div class="uk-transition-fade uk-position-cover uk-position-small uk-overlay uk-overlay-default uk-flex uk-flex-center uk-flex-middle">
                            <div class="uk-text-center">
                                <div class="uk-transition-slide-top-small"><h4 class="uk-margin-remove">{{ client.name }}</h4></div>
                                <div class="uk-transition-slide-bottom-small">
                                    <a href="" uk-icon="icon: facebook" class="uk-margin-small-right"></a>
                                    <a href="" uk-icon="icon: google" class="uk-margin-small-right"></a>
                                    <a href="" uk-icon="icon: instagram" class="uk-margin-small-right"></a>
                                </div>
                            </div>
                        </div>
                    </div>
                </li>
            </ul>

        </div>
      </div>
    </section>
    
  </div>
</template>

<script>
import SharedHeader from '../components/SharedHeader.vue'

export default {
  name: 'Clients',
  components: {
    SharedHeader
  },
  data: () => ({
      clients: [
          {
              name: 'Client1',
              category: 'blue'
          },
          {
              name: 'Client2',
              category: 'white'
          },
          {
              name: 'Client3',
              category: 'black'
          },
          {
              name: 'Client4',
              category: 'black'
          },
          {
              name: 'Client5',
              category: 'blue'
          },
          {
              name: 'Client6',
              category: 'white'
          },
          {
              name: 'Client7',
              category: 'white'
          },
          {
              name: 'Client8',
              category: 'blue'
          }
      ]
  })
}
</script>

<style>

</style>