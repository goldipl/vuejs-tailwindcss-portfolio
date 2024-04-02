<script setup lang="ts">
import HeroComponent from '../components/home/HeroComponent.vue'
import AboutMeSection from '../components/home/AboutMeSection.vue'
import ServicesSection from '../components/home/ServicesSection.vue'
</script>

<template>
  <HeroComponent />
  <AboutMeSection />
  <ServicesSection />
</template>

<style>
.white-shape {
  svg {
    width: 100%;
  }
}
</style>
