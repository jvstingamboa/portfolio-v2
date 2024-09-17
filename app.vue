<script setup lang="ts">
useHead({
  title: 'Justin Gamboa',
  meta: [
    {
      name: 'description',
      content:
        "Justin Gamboa, I'm a passionate developer with a deep interest in technology and all things related to computing. Over the years, I've dedicated myself creating a variety of personal projects, driven by my passion for learning and exploring new technologies.",
    },
    {
      property: 'og:title',
      content: 'Rémi Jara',
    },
    {
      property: 'og:description',
      content:
        "Justin Gamboa, I'm a passionate developer with a deep interest in technology and all things related to computing. Over the years, I've dedicated myself creating a variety of personal projects, driven by my passion for learning and exploring new technologies.",
    },
    {
      property: 'twitter:card',
      content: 'summary',
    },
  ],
});

useSeoMeta({
  title: 'Justin Gamboa',
  description:
    "Justin Gamboa, I'm a passionate developer with a deep interest in technology and all things related to computing. Over the years, I've dedicated myself creating a variety of personal projects, driven by my passion for learning and exploring new technologies.",
  ogTitle: 'Rémi Jara',
  ogDescription:
    "Justin Gamboa, I'm a passionate developer with a deep interest in technology and all things related to computing. Over the years, I've dedicated myself creating a variety of personal projects, driven by my passion for learning and exploring new technologies.",
  twitterCard: 'summary',
});
</script>

<template>
  <div>
    <NuxtPage />
  </div>
</template>
