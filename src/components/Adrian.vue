<template>
  <img :src="absoluteLogoPath" alt="Cannot load logo file" class="center" width="300" height="75">
</template>

<script setup lang="ts">
// Fetch logo path
const absoluteLogoPath = $computed(() => `${import.meta.env.BASE_URL}assets/adrian.png`);
</script>

<style lang="postcss">
.link-list {
  margin: 0;
  li {
    margin: 6px 0;
  }
}
hr-foot {
    border: 0;
    height: 1px;
}
</style>
