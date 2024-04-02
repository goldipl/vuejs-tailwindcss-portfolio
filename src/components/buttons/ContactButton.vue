<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="flex justify-center items-center my-6">
    <RouterLink
      class="text-black px-8 py-3 border border-purple-600 hover:text-white hover:bg-purple-600 hover:border-black transition-all duration-500"
      to="/contact"
      >Skontaktuj się ze mną</RouterLink
    >
  </div>
</template>
