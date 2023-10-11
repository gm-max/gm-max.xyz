<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <div class="card">
  <h1>Hi, I'm Max and I'm truly passionate about bringing people together and building things that help them thrive.</h1>
  </div>
  <div class="divider"></div>
  <div class="card">
  <subtitle>FROM THE GROUND UP</subtitle>
    <paragraph>
      <b>Zero Club</b> (currently) — We're creating the largest longevity community in Europe. With 200+ members discussing Blueprint (Bryan Johnson's longevity protocol), biohacking, and optimizing their health.<br>
      <br>
      <i>"Honestly, well done you guys for making this community high value and no bullshit. Every chat is relevant to me. Been in 30 groups that all sucked but this one is good"</i><br>
    <div class="cta">
      <a class="cta-button" href="https://joinzero.co">Website</a>
    </div>
    </paragraph>
    <paragraph>
      <b>Second Brain:</b> Cultivated a newsletter community of over 100 Substack creators focused on AI, building engaging newsletters, and sharing insider tips.<br>
      <div class="cta">
        <a class="cta-button" href="https://2ndbrainme.substack.com/">Substack Newsletter</a>
      </div>
    </paragraph>
    <paragraph>
      <b>Grin:</b> Built an AR mobile app for 40K+ NFT holders.<br>
       <div class="cta">
        <a class="cta-button" href="https://mirror.xyz/mytyavatar.eth/mzCVwlG7x7w_oZv_u2H7DwVhBuvYp8sRrC-RH9jvuA4">Read more</a>
      </div>
    </paragraph>
    <paragraph>
      <b>The Arch:</b> Connected 1,200+ Web3 founders through events, talks, and partnerships focused on growing their businesses together.<br>
      <div class="cta">
        <a class="cta-button" href="https://twitter.com/jointhearch">Twitter</a>
      </div>
    </paragraph>
    <paragraph>
      <b>Practup:</b> Built a mobile app to connect 25k+ gym and fitness enthusiasts in France.<br>
    </paragraph>

  </div>
  <div class="divider"></div>
  <div class="card">
  <subtitle>I CAN HELP YOU</subtitle>
      <paragraph>
        Branding<br>
        <br>
        Design <br>
        <br>
        No-Coding<br>
        <br>
        Web development (html, css, js, vue.js, next.js, Python)<br>
        <br>
        Community<br>
        <br>
        Content<br>
        <br>
        Social Media<br>
      </paragraph>
      <paragraph>
        I can help you strategically (analyzing, auditing, and coming up with recommendations) or operationally to execute and implement solutions hands-on.
      </paragraph>
      <paragraph>
        I've enough strategic and creative thinking skills to lay out a plan, but also to get shit done.
      </paragraph>
      <paragraph>I’m designer & growth expert with a problem-solver mindset. The only thing that matters to me is to help you reach your goal and boost the metrics you’re trying to boost.
      </paragraph>
      <paragraph>If you got this far, shoot me an <a href="emailto:maximeguerois@gmail.com">email</a> about what you're looking for help on. </paragraph>
  </div>

  <div class="card">
  <div class="divider"></div>
  <subtitle>CONTACT</subtitle>
      <paragraph>
             DMs are opened on <a href="https://twitter.com/gm_maxg">Twitter</a> and <a href="https://t.me/gm_maxg">Telegram</a>.
      </paragraph>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
