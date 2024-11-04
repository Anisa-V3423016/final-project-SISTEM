<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <section class="py-16 bg-gray-100">
      <!-- Header -->
      <div class="text-center mb-12">
        <h2 class="text-sm font-semibold text-gray-500 uppercase">Contact Us</h2>
        <h1 class="text-3xl font-bold text-gray-800">Let’s Start a Conversation</h1>
        <p class="text-gray-600 max-w-md mx-auto mt-4">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.
        </p>
      </div>

      <!-- Contact Info -->
      <div class="container mx-auto px-6 lg:px-8">
        <div class="bg-yellow-400 p-6 rounded-lg text-gray-800 flex justify-between items-start mb-8">
          <div>
            <h3 class="font-semibold text-lg">Working hours</h3>
            <p class="mt-2">Monday To Friday</p>
            <p>9:00 AM to 8:00 PM</p>
            <p class="text-sm text-gray-700 mt-2">Our Support Team is available 24/7</p>
          </div>
          <div>
            <h3 class="font-semibold text-lg">Contact Us</h3>
            <p class="mt-2">020 7993 2905</p>
            <p>hello@insweet.com</p>
          </div>
        </div>

        <!-- Contact Form -->
        <form class="bg-white p-8 rounded-lg shadow-lg space-y-6">
          <div>
            <label class="sr-only" for="name">Full Name</label>
            <input type="text" id="name" placeholder="Full Name" class="w-full border-gray-300 rounded-md shadow-sm focus:ring-2 focus:ring-blue-500 focus:border-blue-500 p-3"/>
          </div>
          <div>
            <label class="sr-only" for="email">Your Email</label>
            <input type="email" id="email" placeholder="Your Email" class="w-full border-gray-300 rounded-md shadow-sm focus:ring-2 focus:ring-blue-500 focus:border-blue-500 p-3"/>
          </div>
          <div class="flex gap-4">
            <div class="w-1/2">
              <label class="sr-only" for="province">Province</label>
              <select id="province" class="w-full border-gray-300 rounded-md shadow-sm focus:ring-2 focus:ring-blue-500 focus:border-blue-500 p-3">
                <option>Province</option>
                <option>Option 1</option>
                <option>Option 2</option>
              </select>
            </div>
            <div class="w-1/2">
              <label class="sr-only" for="city">City</label>
              <select id="city" class="w-full border-gray-300 rounded-md shadow-sm focus:ring-2 focus:ring-blue-500 focus:border-blue-500 p-3">
                <option>City</option>
                <option>Option 1</option>
                <option>Option 2</option>
              </select>
            </div>
          </div>
          <div>
            <label class="sr-only" for="message">Message</label>
            <textarea id="message" placeholder="Message" rows="4" class="w-full border-gray-300 rounded-md shadow-sm focus:ring-2 focus:ring-blue-500 focus:border-blue-500 p-3"></textarea>
          </div>
          <button type="submit" class="w-full bg-blue-600 text-white font-semibold py-3 rounded-md hover:bg-blue-700 focus:ring-2 focus:ring-blue-500 focus:ring-offset-2">Send Message</button>
        </form>
      </div>
    </section>
  </MainLayout>
</template>

<style scoped>
.container {
  max-width: 700px;
}
</style>
