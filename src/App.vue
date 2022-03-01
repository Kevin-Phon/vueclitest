<template>
  <h1>Hi {{name}}</h1>
  <!-- <Modal></Modal> -->
  <Modal/>
</template>

<script>
import Modal from "./components/Modal.vue"
export default {
  data(){
    return{
      name:"Kevin"
    }
  },
  components:{
    // Modal:Modal
    Modal
  }
}
</script>

<style scoped>
  h1{
    color : blue;
  }
</style>