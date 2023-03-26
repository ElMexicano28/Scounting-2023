<template>
  <div :id="funnies">
    <RouterLink :to="#/assets/Adrian.jpg">Adrian</RouterLink>
    <br>
    <RouterLink :to="#/assets/brian.png">Brian</RouterLink>
    <br>
    <RouterLink :to="#/assets/savanna.png">Savanna</RouterLink>
    <br>
    <RouterLink :to="#/assets/caden.png">Caden</RouterLink>
    <br>
    <RouterLink :to="#/assets/stears.png">Mr. Stears</RouterLink>
    <br>
    <RouterLink :to="#/assets/julien.png">Julien</RouterLink>
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
