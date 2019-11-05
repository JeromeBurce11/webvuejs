<template>
  <nav>
       <div class="header">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    
  </nav>
</template>

<script>
export default {
  name: 'header'
}
</script>

<style scoped>
    .header{
        background-color: var(--main-dark-bg-color);
        color: var(--txt-inverse-color);
        font-size: 16px;
        display: flex;
        height: 50px;
    }
    
    .navBtn{
        margin: 15px;
    }

    .navBtn:hover{
        cursor: pointer;
    }
</style>