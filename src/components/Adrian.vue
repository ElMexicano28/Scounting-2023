<template>
  <div :id="funnies">
    <a href="https://ryanhubbs.github.io/2152-Scouting/assets/Adrian.jpg">Adrian</a>
    <br>
    <a href="https://ryanhubbs.github.io/2152-Scouting/assets/brian.png">Brian</a>
    <br>
    <a href="https://ryanhubbs.github.io/2152-Scouting/assets/savanna.png">Savanna</a>
    <br>
    <a href="https://ryanhubbs.github.io/2152-Scouting/assets/caden.png">Caden</a>
    <br>
    <a href="https://ryanhubbs.github.io/2152-Scouting/assets/stears.png">Mr. Stears</a>
    <br>
    <a href="https://ryanhubbs.github.io/2152-Scouting/assets/julian.png">Julien</a>
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
