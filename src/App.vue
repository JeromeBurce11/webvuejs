<template>
  <v-app>
    
      <pageHeader></pageHeader>
   
    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
import pageHeader from '@/components/Header'
export default {
 components:{
   pageHeader
 }
};
</script>
