<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';
import Homesection from './components/Homesection.vue';
</script>

<template>

<div class="main-body">
  <Navbar/>
  <Homesection/>
</div>


</template>

<style scoped>

.main-body{


display: flex;
flex-direction: column;
justify-content: center;

align-items: center;
font-family: "Karla", sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
}
</style>
