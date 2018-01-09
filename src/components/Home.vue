<template>
  <div style="padding-top: 150px;" class="container-fluid">
    <banner></banner>
    <premium></premium>
    <standart></standart>
  </div>
</template>

<script>
import  Banner from './Home/Banner.vue'
import Premium from './Home/Premium.vue'
import Standart from './Home/Standart'
export default {
components:{
  Banner,
  Premium,
  Standart
},
  data () {
    return {

    }
  }
}
</script>


<style scoped>

</style>
