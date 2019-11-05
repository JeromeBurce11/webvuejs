<template>
  <nav>
       <div class="header">
      <h1><router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link></h1>
       <h1 class="companyName">Eco-Green</h1>
    </div>
    
  </nav>
</template>

<script>
export default {
  name: 'header'
}
</script>

<style scoped>
    .companyName{
      margin-left:80%;
    }
    .header{
        background-color: yellowgreen;
        background-size: cover;
        color: var(--txt-inverse-color);
        font-size: 16px;
        display: flex;
        height: 50px;
    }
    
    .navBtn{
        margin: 15px;
    }
    h1{
      color: white;
    }

    .navBtn:hover{
        cursor: pointer;
    }
</style>