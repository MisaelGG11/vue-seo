<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

<script setup lang="ts">
import { useHead } from '@vueuse/head';

useHead({
  title: 'Acerca de - Vue Meta Demo',
  meta: [
    { name: 'description', content: 'Página acerca de con metadatos SEO' }
  ]
});
</script>
