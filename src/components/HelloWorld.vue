<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div class="card">
  <h1>Hi, I'm Max and I'm truly passionate about connecting people each others and creating things to help them.</h1>
  </div>
  <div class="card">
  <subtitle>COMMUNITIES FROM O TO 1</subtitle>
    <paragraph>
    <ul>
          <li><b>Zero Club (currently):</b> 200+ biohackers and longevity enthusiasts in Europe. <a href="https://joinzero.co">Join us</a>.</li>
          <li><b>Second Brain:</b> 100+ susbstack creators. <a href="https://2ndbrainme.substack.com/">Check it out</a>.</li>
          <li><b>Grin:</b> 40k+ NFT enthusiasts. <a href="https://mirror.xyz/mytyavatar.eth/mzCVwlG7x7w_oZv_u2H7DwVhBuvYp8sRrC-RH9jvuA4">Read more here</a>.</li>
          <li><b>The Arch:</b> 1200+ web3 builders, founders and contributors in France. <a href="https://twitter.com/jointhearch">Check out the Twitter</a>.</li>
          <li><b>Practup:</b> 25k+ gym and fitness enthusiasts in France.</li>
    </ul>
    </paragraph>
  </div>

  <div class="card">
  <subtitle>I CAN HELP YOU</subtitle>
      <paragraph>
        I can help you <b>strategically (analyzing, auditing, and coming up with recommendations) or operationally (executing campaigns).</b>
      </paragraph>
      <paragraph>
        I've enough strategic and creative thinking skills to lay out a plan, but also to get shit done.
      </paragraph>
      <paragraph>I’m community & growth expert with a problem-solver mindset. The only thing that matters to me is to help you reach your goal and boost the metrics you’re trying to boost.
      </paragraph>
  </div>

  <div class="card">
  <subtitle>CONTACT</subtitle>
      <paragraph>
             <b>DMs are opened</b> on <a href="https://twitter.com/gm_maxg">Twitter</a> and <a href="https://t.me/gm_maxg">Telegram</a>. I can do <a href="emailto:maximeguerois@gmail.com">email</a> too.
      </paragraph>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
