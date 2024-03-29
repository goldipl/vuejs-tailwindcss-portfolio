<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <header
    class="w-full max-w-[1280px] m-auto before:content-[''] before:block before:bg-gradient-to-t from-purple-600 from-15% to-black before:top-0 before:left-0 before:absolute before:h-16 before:w-full mb-4"
  >
    <div
      class="relative bg-gradient-to-t from-purple-600 from-15% to-black flex justify-between items-center h-16"
    >
      <RouterLink to="/">
        <p class="relative text-white font-rock text-2xl top-[-4px]">
          Marcin Godlewski
          <span class="absolute bottom-[-16px] right-[-16px] text-sm">Web Developer</span>
        </p>
      </RouterLink>
      <nav class="flex justify-between items-center w-3/5">
        <RouterLink class="text-gray-300 text-lg hover:text-white" to="/">Home</RouterLink>
        <RouterLink class="text-gray-300 text-lg hover:text-white" to="/about-me"
          >About me</RouterLink
        >
        <RouterLink class="text-gray-300 text-lg hover:text-white" to="/portfolio"
          >Portfolio</RouterLink
        >
        <RouterLink class="text-gray-300 text-lg hover:text-white" to="/references"
          >References</RouterLink
        >
        <RouterLink class="text-gray-300 text-lg hover:text-white" to="/contact"
          >Contact</RouterLink
        >
      </nav>
    </div>
  </header>
</template>
