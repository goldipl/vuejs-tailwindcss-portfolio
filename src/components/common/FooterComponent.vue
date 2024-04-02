<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <footer
    class="relative w-full m-auto before:content-[''] before:block before:bg-gradient-to-t from-purple-600 from-15% to-black before:top-0 before:left-0 before:absolute before:h-16 before:w-full"
  >
    <div
      class="relative mx-auto max-w-[1200px] bg-gradient-to-t from-purple-600 from-15% to-black flex justify-between items-center h-16"
    >
      <RouterLink to="/">
        <p class="text-white">Marcin Godlewski, Front-end Developer &copy; 2024</p>
      </RouterLink>
      <nav class="flex justify-end items-center w-3/5">
        <a
          class="text-gray-300 text-sm hover:text-white m-4"
          href="https://github.com/goldipl"
          target="_blank"
          >GitHub</a
        >
        <a
          class="text-gray-300 text-sm hover:text-white m-4"
          href="https://www.linkedin.com/in/marcin-godlewski-153897139/"
          target="_blank"
          >LinkedIn</a
        >
        <span class="text-gray-300 text-sm m-4"
          >E-mail:
          <a
            class="text-gray-300 text-sm hover:text-white"
            href="mailto:mgodlewski92@gmail.com"
            target="_blank"
            >mgodlewski92@gmail.com</a
          ></span
        >
      </nav>
    </div>
  </footer>
</template>
