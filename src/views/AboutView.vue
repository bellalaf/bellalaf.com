<script setup>
import About from '../components/AboutSection.vue'
</script>

<template>
  <div class="wrapper">
    <About></About>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
