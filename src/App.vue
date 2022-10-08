<template>
  <div id="app">
    <HeaderComponent  :navbartext="navbar" />
    <FormComponent />
    <ServiceComponent />
    <ReviewsComponent />
    <GymComponent />
    <TrainersComponent />
    <NewsComponent />
    <FooterComponent />
    <SecondFooter />
    
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FormComponent from './components/FormComponent.vue';
import ServiceComponent from './components/ServiceComponent.vue';
import ReviewsComponent from './components/ReviewsComponent.vue';
import GymComponent from './components/GymComponent.vue';
import TrainersComponent from './components/TrainersComponent.vue';
import NewsComponent from './components/NewsComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import SecondFooter from './components/SecondFooter.vue';


export default {
  name: 'App',
  components: {
    HeaderComponent,
    FormComponent,
    ServiceComponent,
    ReviewsComponent,
    GymComponent,
    TrainersComponent,
    NewsComponent,
    FooterComponent,
    SecondFooter
},
data () {
  return {
    navbar : [
      {
        text: 'HOME',
        position: 1

      },

      {
        text: 'ABOUT US',
        position: 2
      },

      {
        text: 'FACILITIES',
        position: 3
      },

      {
        text: 'MEMBERSHIP',
        position: 4
      },

      {
        text: 'TESTIMONIALS',
        position: 5
      },

      {
        text: 'BLOG',
        position: 6
      }
    ]
  }
}
}
</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
