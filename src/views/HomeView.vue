<script setup lang="ts">
import HeroComponent from '../components/home/HeroComponent.vue'
import AboutMeSection from '../components/home/AboutMeSection.vue'
import ServicesSection from '../components/home/ServicesSection.vue'
import SkillsSection from '../components/home/SkillsSection.vue'
import ToolsSection from '../components/home/ToolsSection.vue'
import ExperienceSection from '../components/home/ExperienceSection.vue'
</script>

<template>
  <HeroComponent />
  <AboutMeSection />
  <ServicesSection />
  <SkillsSection />
  <ToolsSection />
  <ExperienceSection />
</template>

<style>
.white-shape {
  svg {
    width: 100%;
  }
}
</style>
