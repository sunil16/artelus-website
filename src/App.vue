<template>
  <div id="app">
    <Header/>
  </div>
</template>

<script>
// import 'bootstrap/dist/css/bootstrap.css'
// import 'bootstrap-vue/dist/bootstrap-vue.css'
import Header from './components/Header.vue';
// import Home from './components/Home.vue'
// import Vision from './components/vision.vue'
//
// import Mission from './components/mission.vue'


export default {
  name: 'app',
  components: {
    Header
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
  /* margin-top: 60px; */
}


</style>
