<template>
  <div :id="funnies">
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/assets/Adrian.jpg">Adrian</a>
    <br>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/assets/brian.png">Brian</a>
    <br>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/assets/savanna.png">Savanna</a>
    <br>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/assets/caden.png">Caden</a>
    <br>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/assets/stears,png">Mr. Stears</a>
    <br>
    <a href="https://elmexicano28.github.io/Scounting-2023/assets/assets/julien.png">Julien</a>
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
