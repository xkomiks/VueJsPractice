<script setup lang="ts">
import AppHeader from '@/components/AppHeader.vue';
</script>

<template>
  <AppHeader/>
  <main>
    <RouterView/>
  </main>
</template>

<style scoped>
main {
  padding-top: 1rem;
}
</style>
