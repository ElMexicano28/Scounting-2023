<template>
  <div :id="funnies">
    <RouterLink :to="/assets/Adrian.jpg">Adrian</RouterLink>
    <RouterLink :to"/assets/brian.png">Brian</a>
    <RouterLink :to="/assets/savanna.png">Savanna</a>
    <RouterLink :to="/assets/caden.png">Caden</a>
    <RouterLink :to="/assets/stears.png">Mr. Stears</a>
    <RouterLink :to="/assets/julien.png">Julien</a>
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
