<template>
  <div id="app">
    <!-- <HelloWorld msg="Welcome to Vue.js App"/> -->
    <navbar/>
    <imgtron/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import navbar from './components/nav.vue'
import imgtron from './components/img_trons.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld,
    navbar,
    imgtron
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
}
</style>
