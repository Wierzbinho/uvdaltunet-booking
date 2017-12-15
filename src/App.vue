<template>
  <div id="app">
    <h1>VELKOMMEN TIL UVDALTUNET</h1>
    <ImageCarousel/>
    <ContentContainer/>
    <!--<router-view/>-->
  </div>
</template>

<script>
import ImageCarousel from './components/carousel.vue';
import ContentContainer from './components/content-container.vue';

export default {
  name: 'app',
  components: {
    ImageCarousel,
    ContentContainer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}
</style>
