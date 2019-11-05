<template>
  <v-card>
    <v-row>
      <v-col>
        <img :src="picture" />
      </v-col>
      <v-col cols='10' class="text-left">
        <h1>{{name}}</h1>
      </v-col>
    </v-row>
  </v-card>
</template>
<script>
export default {
  name: "dev",
  props: {
    name: String,
    picture: String
  }
};
</script>
<style scoped>
  img{
   width: 100px;
    height: 100px;
  }
</style>