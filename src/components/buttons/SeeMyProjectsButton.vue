<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="flex justify-center items-center my-4">
    <RouterLink
      class="text-gray-300 px-8 py-3 border border-purple-600 hover:text-purple-600 hover:bg-white transition-all duration-500"
      to="/portfolio"
      >Zobacz więcej moich projektów</RouterLink
    >
  </div>
</template>
