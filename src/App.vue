<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="" target="_blank">
      <img src="./assets/fuckassyoutubeemoji.png" class="logo" alt="fuckassyoutubeemoji" />
    </a>
    <a href="" target="_blank">
      <img src="./assets/fuckassyoutubeemoji.png" class="logo" alt="fuckassyoutubeemoji" />
    </a>
  </div>
  <HelloWorld msg="Farm + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #9F1A8Faa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
