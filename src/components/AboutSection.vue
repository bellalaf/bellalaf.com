<script setup>
</script>

<template>
  <div class="greetings">
    <div class="heading">
      <h1 class="purple">About</h1>
      <img src="../assets/hiking2025.jpg" alt="Bella Lafrenais" width="300">
      <br>
    </div>
    <h3>Since relocating to Edinburgh, I've been working at People's Postcode Lottery. Currently working with lots of CDK and Python lambdas. </h3>
    <br>
    <h3>I love reading, boardgames and am determined to make my hiking boot purchase worth it - many Munros to come.</h3>
  </div>
</template>

<style scoped>
  h1 {
  font-family: Verdana,serif;
  font-weight: 600;
  font-size: 2.9rem;
  color: #726691;
}

  h3 {
  font-size: 1.2rem;
  font-family: Verdana,serif;
}

  img {
    padding: 20px;
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

  .greetings {
    display: inline-flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    position: relative;
}
  .heading {
    display: inline-flex;
    align-items: center;
    justify-content: space-around;
    position: relative;
    flex-grow: 1;
  }

  @media (min-width: 1024px) {
  .greetings h1,
  .greetings h3,
  .greetings h5 {
  text-align: left;
}
}
</style>