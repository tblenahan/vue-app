<template>
  <b-container fluid="sm">
    <b-row class="justify-content-around" >
      <tron v-for="(image, x) in images" :key="x" v-bind:style="{ backgroundImage: 'url(' + image + ')' }"/>
    </b-row>
  </b-container>
</template>

<script>
  import Tron from './tron.vue'

  export default {
    name: 'imgtron',
    components: {
      Tron
    },
    data() {
      return {
        images: [
          '../assets/km-dead-1.jpg',
          '../assets/km-squat-1.jpg'
        ]
      }
    }
  }

</script>

<style>
  .img-1 {
    /* The image used */
    background-image: url("../assets/km-dead-1.jpg");

    /* Half height */
    /* height: 100%; */

    /* Center and scale the image nicely */
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }
  .img-2 {
    /* The image used */
    background-image: url("../assets/km-squat-1.jpg");

    /* Half height */
    /* height: 100%; */

    /* Center and scale the image nicely */
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }
</style>