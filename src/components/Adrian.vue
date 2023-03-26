<template>
  <div :id="funnies">
    <img :src="adrian" alt="Cannot load logo file" class="center" width="1700" height="2000">
    <br>
    <img :src="caden" alt="Cannot load logo file" class="center" width="1700" height="2000">
    <br>
  </div>
</template>

<script setup lang="ts">
// Fetch logo path
const adrian = $computed(() => `${import.meta.env.BASE_URL}assets/Adrian.jpg`);
const caden = $computed(() => `${import.meta.env.BASE_URL}assets/caden.png`);
const absoluteLogoPath = $computed(() => `${import.meta.env.BASE_URL}assets/Adrian.jpg`);
const absoluteLogoPath = $computed(() => `${import.meta.env.BASE_URL}assets/Adrian.jpg`);
const absoluteLogoPath = $computed(() => `${import.meta.env.BASE_URL}assets/Adrian.jpg`);
const absoluteLogoPath = $computed(() => `${import.meta.env.BASE_URL}assets/Adrian.jpg`);
</script>

<style lang="postcss">
.funnies {
  background-image:absoluteLogoPath
}
</style>
