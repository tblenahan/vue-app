<template>
  <b-container fluid="sm">
    <b-row class="justify-content-around">

      <b-col sm="6" class="mt-4">
        <!-- style="background-image: url('../assets/km-squat-1.jpg');" -->
        <b-jumbotron class="img-1" lead="Bootstrap v4 Components for Vue.js 2">
          <p>For more information visit website</p>
        </b-jumbotron>
      </b-col>

      <b-col sm="6" class="mt-4">
        <!-- style="background-image: url('../assets/km-dead-1.jpg');" -->
        <b-jumbotron class="img-2" lead="Bootstrap v4 Components for Vue.js 2">
          <p>For more information visit website</p>
        </b-jumbotron>
      </b-col>

    </b-row>
  </b-container>
</template>

<script>

export default {
  name: 'imgtron',
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