<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="purple">{{ msg }}</h1>
    <h3>Software Developer*  <a href="https://www.postcodelottery.co.uk/" target="_blank" rel="noopener">@postcodelottery</a></h3>
    <h3>Aiming to make the world a slightly better place, one commit at a time.</h3>
    <h5>*backend gal only, this site is so far the extent of my frontend abilities</h5>
  </div>
</template>

<style scoped>
h1 {
  font-family: Verdana,serif;
  font-weight: 600;
  font-size: 2.9rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
  font-family: Verdana,serif;
}

h5 {
  font-family: Verdana,serif;
  position: relative;
  top: 10px;
}

a {
  color: #2c3e50;
}

a:hover {
  background-color: #0e0b17;
  color: #cc79fc;
}

.greetings h1,
.greetings h3
.greetings h5 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3,
  .greetings h5 {
    text-align: left;
  }
}
</style>
