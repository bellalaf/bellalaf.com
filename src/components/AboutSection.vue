<script setup>
</script>

<template>
  <div class="greetings">
    <div class="heading">
      <h1 class="purple">About</h1>
      <img src="../assets/hiking2025.jpg" alt="Bella Lafrenais" width="300">
    </div>
    <div class="text">
      <h4>Since relocating to Edinburgh, I've been working at People's Postcode Lottery and learning more than I ever
        thought I would about AWS and the domain of payments. I also caught the LazyVim bug...</h4>
      <h4>Alongside <a href="https://www.linkedin.com/in/saramdavies/" target="_blank" rel="noopener">Sara Davies</a>, I
        co-founded a Diversity in Tech group at the lottery, and through that I've had the opportunity to work alongside
        university students via <a href="https://edinburghhoppers.com/sponsors" target="_blank"
          rel="noopener">Hoppers</a> and the wonderful people doing wonderful things over at <a href="https://ada.scot/"
          target="_blank" rel="noopener">AdaScot</a>. I've been involved in organising office visits, workshops, IWD
        celebrations and so much more.</h4>
      <br>
      <h4>I love reading, skiing, boardgames and, after an accidental subscription to AllTrails, hiking.</h4>
    </div>
  </div>
</template>

<style scoped>
h1 {
  font-family: Verdana, serif;
  font-weight: 600;
  font-size: 2.9rem;
  color: #726691;
}

h3 {
  font-size: 1.2rem;
  font-family: Verdana, serif;
}

img {
  padding: 10px;
  text-align: center;
}

h5 {
  font-family: Verdana, serif;
  position: relative;
  top: 10px;
}

.greetings {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}

.heading {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 20px;
  width: 90%;
}

@media (max-width: 768px) {
  .heading {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .heading img {
    width: 80%;
    max-width: 300px;
  }
}
</style>