<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="card">
    <a target="_blank">
      <img src="./assets/pfp.jpeg" class="logo" alt="yo, I'm Max :)" />
    </a>
  </div>
  <HelloWorld msg="Max" />
</template>

<style scoped>
.logo {
  max-width: 300px;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
