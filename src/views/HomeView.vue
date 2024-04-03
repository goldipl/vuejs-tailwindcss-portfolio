<script setup lang="ts">
import HeroComponent from '../components/home/HeroComponent.vue'
import AboutMeSection from '../components/home/AboutMeSection.vue'
import ServicesSection from '../components/home/ServicesSection.vue'
import SkillsSection from '../components/home/SkillsSection.vue'
import ToolsSection from '../components/home/ToolsSection.vue'
import ExperienceSection from '../components/home/ExperienceSection.vue'
import ContactSection from '../components/home/ContactSection.vue'
import PortfolioSection from '../components/home/PortfolioSection.vue'
import ReferencesSection from '../components/home/ReferencesSection.vue'
</script>

<template>
  <HeroComponent />
  <AboutMeSection />
  <ServicesSection />
  <SkillsSection />
  <ToolsSection />
  <ExperienceSection />
  <ContactSection />
  <PortfolioSection />
  <ReferencesSection />
</template>

<style>
.white-shape {
  svg {
    width: 100%;
  }
}

@media (max-width: 767px) {
  .white-shape {
    svg {
      width: 150%;
      height: 36px;
    }
  }
}
</style>
