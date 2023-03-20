<template>
  <div id="adrian-container">
    <Suspense>
      <template #default>
        <HomePage />
      </template>
      <template #fallback>Loading...</template>
    </Suspense>
  </div>
</template>

<script setup lang="ts">
import HomePage from "@/components/Adrian.vue";
</script>

<style>
#adrian-container {
  display: grid;
  justify-content: center;
}
</style>
