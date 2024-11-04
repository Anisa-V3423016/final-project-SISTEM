<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <section class="bg-gray-100 py-16">
      <!-- About Us Section -->
      <div class="container mx-auto px-6 lg:px-8 text-center">
        <h1 class="text-3xl font-semibold text-gray-800 mb-4">We are a team of content writers who share their learnings</h1>
        <p class="text-gray-600 max-w-xl mx-auto">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        </p>
      </div>

      <!-- Statistics Section -->
      <div class="container mx-auto mt-10 grid grid-cols-3 gap-6 text-center">
        <div class="bg-white p-8 rounded-lg shadow-md">
          <h3 class="text-4xl font-bold text-blue-500">12+</h3>
          <p class="text-gray-600">Blogs Published</p>
        </div>
        <div class="bg-white p-8 rounded-lg shadow-md">
          <h3 class="text-4xl font-bold text-blue-500">18K+</h3>
          <p class="text-gray-600">Views on Filasawat</p>
        </div>
        <div class="bg-white p-8 rounded-lg shadow-md">
          <h3 class="text-4xl font-bold text-blue-500">30K+</h3>
          <p class="text-gray-600">Total Active Users</p>
        </div>
      </div>

      <!-- Mission Section -->
      <div class="container mx-auto mt-16 grid grid-cols-2 gap-6 text-center">
        <div class="bg-white p-8 rounded-lg shadow-md">
          <h4 class="text-2xl font-semibold text-gray-800 mb-4">Our Mission</h4>
          <p class="text-gray-600">
            Creating valuable content for creatives all around the world. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </div>
        <div class="bg-white p-8 rounded-lg shadow-md">
          <h4 class="text-2xl font-semibold text-gray-800 mb-4">Our Vision</h4>
          <p class="text-gray-600">
            A platform that empowers individuals to improve. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </div>
      </div>
    </section>
  </MainLayout>
</template>

<style scoped>
.container {
  max-width: 1200px;
}
</style>
