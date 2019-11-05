<template>
  <div class="home">
    <div class="home">
    <dev v-bind:Homepage = "require('@/assets/home.png')" v-bind:name="'Eco-Green!'"></dev>
  </div>
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
