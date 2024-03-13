<script setup>

</script>
<template>
  <div class="nav">
  <RouterLink to ="/">Home</RouterLink>
  <RouterLink to ="/about">About</RouterLink>
  <RouterLink to ="/services">Services</RouterLink>
  <RouterLink to ="/contact">Contact</RouterLink>
  <RouterLink to ="/login">Login</RouterLink>
  <RouterLink to ="/signup">Signup</RouterLink>    
  </div>
  <router-view></router-view>
  
</template>

<style>
.nav{
  font-size: 30px;
  font-weight: bolder;
  background-color: #4e4d48;
  padding: 10px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
.nav a {
  color: #fff;
    cursor: pointer;
    text-decoration: none;
}
</style>