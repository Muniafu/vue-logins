<script setup>
import { ref } from "vue";

const count = ref(0)

</script>

<template>
  <div class="app-container">
    <h1>Welcome Home</h1>
    <div v-if="!showView" class="head-container">
      <h2> Counter App</h2>
      <button @click="count++"> Increment {{ number }}</button>
      <button @click="count--"> Dencrement {{ number }}</button>
      <p>{{ count }}</p>
    </div>
    </div>

  
</template>

<style>
h1{
  display: flex;
  flex: content;
  padding: 10px;
  align-items: center;
  background-color: blue;
}
.head-container{
  margin: 25px;
  padding: 0 10px 20px;
  font-weight: bolder;
  color: #147dda;
}
.head-container button{
  margin: 25px;
  padding: 5px;
}
</style>
