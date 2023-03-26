<template>
  <div :id="funnies">
    <RouterLink :to="/assets/Adrian">Adrian</RouterLink>
    <br>
    <RouterLink :to="/assets/brian">Brian</RouterLink>
    <br>
    <RouterLink :to="/assets/savanna">Savanna</RouterLink>
    <br>
    <RouterLink :to="/assets/caden">Caden</RouterLink>
    <br>
    <RouterLink :to="/assets/stears">Mr. Stears</RouterLink>
    <br>
    <RouterLink :to="/assets/julien">Julien</RouterLink>
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
