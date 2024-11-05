<script setup lang="ts">
const title = "John Doe"
const subtitle = "Full Stack Developer"
const description = "I build modern web applications with a focus on clean code and great user experience."
</script>

<template>
  <section id="home" class="min-h-screen flex items-center justify-center bg-gradient-to-br from-gray-900 to-gray-800 text-white">
    <div class="text-center">
      <h1 class="text-5xl font-bold mb-4">{{ title }}</h1>
      <h2 class="text-3xl text-blue-400 mb-6">{{ subtitle }}</h2>
      <p class="text-xl text-gray-300 max-w-2xl mx-auto">{{ description }}</p>
      <div class="mt-8">
        <a href="#projects" class="bg-blue-500 hover:bg-blue-600 text-white px-6 py-3 rounded-lg transition-colors">
          View My Work
        </a>
      </div>
    </div>
  </section>
</template>