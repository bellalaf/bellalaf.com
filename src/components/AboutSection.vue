<script setup>
</script>

<template>
  <div class="greetings">
    <div class="heading">
      <h1 class="purple">About</h1>
      <br>
      <img src="../assets/headshot2023.jpeg" alt="Bella Lafrenais" width=300>
    </div>
    <h3>I am currently working at Reece, coding up a storm on the backend of our Next Gen POS project. I mostly work in a Java microservice world, but we also have a few Kotlin services that I am enjoying fiddling with. </h3>
    <br>
    <h3>When I'm not in our lovely new Cremorne office or working with GPN to get gender minorities into tech; I enjoy bouldering, reading, boardgames and the occasional triathlon.</h3>
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