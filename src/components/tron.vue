<template>
    <b-col sm="6" class="mt-4">
        <!-- style="background-image: url('../assets/km-squat-1.jpg');" -->
        <b-jumbotron :style={style}>
          <p>For more information visit website</p>
        </b-jumbotron>
      </b-col>
</template>

<script>
// Vue.component('tron', {
//     prop: {
//         bgImage: {
//             type: String,
//             default: ""
//         }
//     },
//     template: 
//         <b-col sm="6" class="mt-4">
//             <b-jumbotron style={{bgStyle}}>
//             <p>For more information visit website</p>
//             </b-jumbotron>
//         </b-col>,
//     computed: {
//         bgStyle() {
//             return{
//                 "background-img": this.bgImage
//             };
//         }
//     }
// })

export default {
  name:  'tron',
  prop: {
      bgImage: {
          type: String,
          default: ""
      },
  },
  data() {
    return {
      style: "background-image:" + this.bgImage,
    }
  }
}

</script>