<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="flex justify-center items-center my-6">
    <RouterLink
      class="text-white px-8 py-3 border border-purple-600 hover:text-purple-600 hover:border-white hover:bg-white transition-all duration-500"
      to="/portfolio"
      >Zobacz moje projekty</RouterLink
    >
  </div>
</template>
