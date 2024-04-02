<script lang="ts">
import { defineComponent } from 'vue'
import PortfolioButton from '../buttons/PortfolioButton.vue'

export default defineComponent({
  name: 'ExperienceSection',
  components: {
    PortfolioButton
  }
})
</script>

<template>
  <section id="portfolio-section" class="pt-40 pb-64">
    <div class="wrapper">
      <h1 class="text-center text-4xl mb-6">Portfolio</h1>
      <p class="text-center">Zapraszam do zapoznania się z moim portfolio</p>
      <p class="text-center">
        Znajdziecie w nim wszystkie wykonane dotychczas projekty, a także aktualne projekty.
      </p>
      <PortfolioButton />
    </div>
  </section>
</template>

<style scoped>
#portfolio-section {
  position: relative;
  height: auto;
  background-image: linear-gradient(
      to top,
      rgba(0, 255, 247, 0.1294117647) -125%,
      rgba(0, 0, 0, 0.5294117647) 95%
    ),
    url(./../../assets/img/hero/hero.jpg);
  color: #ffffff;
  background-position: bottom;
  background-repeat: no-repeat;
  background-size: 600vh;
  background-attachment: fixed;
}
</style>
