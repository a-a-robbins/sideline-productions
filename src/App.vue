<script setup lang="ts">
import NavigationBar from './components/NavigationBar.vue'
import PhotoGallery from './components/PhotoGallery.vue'
</script>

<template>
  <div class="h-screen bg-gradient-to-br from-gray-500 to-gray-900">
    <NavigationBar></NavigationBar>

    <div class="flex justify-center mt-16">
      <h1 class="text-7xl bg-blue-500">Sideline Productions LOGO</h1>
    </div>

    <div class="mt-12 flex justify-center">
      <PhotoGallery></PhotoGallery>
    </div>

    <div class="flex flex-col items-center mt-8">
      <button class="rounded-md bg-blue-500 text-white p-6">CTA Button</button>
    </div>
  </div>
</template>
