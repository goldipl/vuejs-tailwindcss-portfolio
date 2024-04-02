<script setup lang="ts">
import HeaderComponent from './components/common/HeaderComponent.vue'
import FooterComponent from './components/common/FooterComponent.vue'
</script>

<template>
  <HeaderComponent />
  <RouterView />
  <FooterComponent />
</template>

<style scoped>
@media (min-width: 1024px) {
}
</style>
