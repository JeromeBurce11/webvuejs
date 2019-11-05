<template>
  <div class="about">
    <dev v-bind:picture = "require('@/assets/burce.jpg')" v-bind:name="'Jerome P. Burce'"></dev>
    <dev v-bind:picture = "require('@/assets/cabia-an.jpg')" v-bind:name="'John Patrick Cabia-an'"></dev>
    <dev v-bind:picture = "require('@/assets/morre.jpg')" v-bind:name="'Josephine Morre'"></dev>
    <dev v-bind:picture = "require('@/assets/rufo.jpg')" v-bind:name="'Irish Rufo'"></dev>
  </div>


  </template>

<script>
import dev from "@/components/developers";
export default {
  components:{
    dev
  }
};
</script>
<style scoped>
  
</style>



