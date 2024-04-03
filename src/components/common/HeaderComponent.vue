<script setup lang="ts">
import { RouterLink } from 'vue-router'
import TapbarComponent from '@/components/common/TapbarComponent.vue'
</script>

<template>
  <header
    class="flex items-center md:block relative w-full m-auto before:content-[''] before:hidden md:before:block before:bg-gradient-to-t from-purple-600 from-15% to-black before:top-0 before:left-0 before:absolute before:h-16 before:w-full mb-4"
  >
    <div
      class="relative mx-auto max-w-[1200px] bg-gradient-to-t from-purple-600 from-15% to-black flex justify-center md:justify-between items-center h-14 md:h-16 w-full"
    >
      <RouterLink to="/">
        <p class="relative text-white font-megrim text-3xl md:text-4xl top-[-6px]">
          Marcin Godlewski
          <span class="absolute bottom-[-11px] md:bottom-[-16px] right-0 text-xs md:text-sm"
            >Front-end Developer</span
          >
        </p>
      </RouterLink>
      <nav class="hidden md:flex justify-between items-center w-3/5">
        <RouterLink class="text-gray-300 text-lg hover:text-white" to="/">Home</RouterLink>
        <RouterLink class="text-gray-300 text-lg hover:text-white" to="/about-me"
          >O mnie</RouterLink
        >
        <RouterLink class="text-gray-300 text-lg hover:text-white" to="/portfolio"
          >Portfolio</RouterLink
        >
        <RouterLink class="text-gray-300 text-lg hover:text-white" to="/references"
          >Referencje</RouterLink
        >
        <RouterLink class="text-gray-300 text-lg hover:text-white" to="/contact"
          >Kontakt</RouterLink
        >
      </nav>
    </div>
  </header>
  <TapbarComponent />
</template>
