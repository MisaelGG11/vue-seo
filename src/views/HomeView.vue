<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'

import { useHead } from '@vueuse/head';

useHead({
  title: 'Inicio - Vue Meta Demo',
  meta: [
    { name: 'description', content: 'Página de inicio con metadatos SEO en Vue 3 y prueba para minecraft' },
    { name: 'keywords', content: 'vue, vue3, vue-router, vue-meta, minecraft' },
    { name: 'author', content: 'Misael Gómez' },
    { property: 'og:title', content: 'Inicio - Vue Meta Demo' },
    { property: 'og:description', content: 'Página de inicio con metadatos SEO en Vue 3 y prueba para minecraft' },
    { property: 'og:image', content: '/path/to/image.jpg' },
    { property: 'og:url', content: window.location.href }
  ]
});
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template>
