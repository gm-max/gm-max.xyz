<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div class="card">
  <h1>Max Guerois</h1>
  </div>
  <div class="card">
    Hey there! I'm Max, also known as Maxime in France. I'm just a guy who's passionate about creating things for others.
  </div>
  <div class="card">
    Currently, I'm helping creators leverage their community through AI experiences. It's called <a href="https://second-brain.me">Secondbrain</a>.
  </div>
  <div class="card">
    Previously, focused on making web3 social with Grin, the first photo-sharing app for anon
    integrating NFTs as filter, <a href="https://mirror.xyz/mytyavatar.eth/mzCVwlG7x7w_oZv_u2H7DwVhBuvYp8sRrC-RH9jvuA4">more here</a>.
  </div>
  <div class="card">
      DMs are opened on <a href="https://twitter.com/gm_maxg">Twitter</a> and <a href="https://t.me/gm_maxg">Telegram</a>. I can do <a href="emailto:maximeguerois@gmail.com">email</a> too.
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
