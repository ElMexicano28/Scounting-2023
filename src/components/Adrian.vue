<template>
  <div :id="funnies">
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/Adrian.jpg">Adrian</a>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/brian.png">Brian</a>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/savanna.png">Savanna</a>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/caden.png">Caden</a>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/stears.png">Mr. Stears</a>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/julien.png">Julien</a>
  </div>
</template>

<script setup lang="ts">
// Fetch logo path
//const adrian = $computed(() => `${import.meta.env.BASE_URL}assets/Adrian.jpg`);
//const caden = $computed(() => `${import.meta.env.BASE_URL}assets/caden.png`);
</script>

<style lang="postcss">
.funnies {
  background-image:absoluteLogoPath
}
</style>
