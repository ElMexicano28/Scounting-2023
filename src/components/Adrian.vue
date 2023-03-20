<template>
  <div :id="funnies">
    <img :src="absoluteLogoPath" alt="Cannot load logo file" class="center">
  </div>
</template>

<script setup lang="ts">
// Fetch logo path
const absoluteLogoPath = $computed(() => `${import.meta.env.BASE_URL}assets/Adrian.jpg`);
</script>

<style lang="postcss">
.funnies {
  background-image:absoluteLogoPath
}
</style>
