<template>
  <div class="flex flex-col items-center text-center w-80 mx-auto">
    <img height="120" width="120" :src="imageUrl" alt="Info image" />
    <h2 class="mt-4 text-2xl font-medium">{{ title }}</h2>
    <p class="text-gray-400 mt-2">{{ description }}</p>
  </div>
</template>

<script setup>
defineProps({
  title: String,
  description: String,
  imageUrl: String
})
</script>

<style></style>
