<script setup>
</script>

<template>
  <header>
    <img alt="RL icon" class="logo" src="./assets/rl-icon.svg" />

    <div class="wrapper">
      <h1 class="title"> "Welcome to Your Rockt League Companion"</h1>
    </div>
  </header>

  <main>
      hey
  </main>
</template>





<style scoped>
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 100;
  font-size: 40px;
  color: #35495e;
  letter-spacing: 1px;
}

header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
