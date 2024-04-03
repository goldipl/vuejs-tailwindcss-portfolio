<script lang="ts">
import { defineComponent } from 'vue'
import AboutMeButton from '../buttons/AboutMeButton.vue'

export default defineComponent({
  name: 'ExperienceSection',
  components: {
    AboutMeButton
  }
})
</script>

<template>
  <section
    id="about-me-section"
    class="wrapper flex flex-col md:flex-row items-center md:items-start my-12 md:my-20 md:my-24"
  >
    <div class="mb-8 md:mb-0" data-aos="fade-right" data-aos-duration="1000">
      <div class="img-animation w-64 mb-2 md:mb-4">
        <img
          src="./../../assets/img/home/about_me/cv-photo.jpg"
          alt="Zdjęcie profilowe"
          width="300"
          height="300"
        />
      </div>
      <div class="flex flex-col items-center">
        <p class="text-center mx-4">Front-end Developer</p>
        <strong class="inline-flex text-center">mgr inż. Marcin Godlewski</strong>
      </div>
    </div>
    <div class="mx-4 md:ms-8" data-aos="fade-left" data-aos-duration="1000">
      <h2 class="text-center md:text-left text-3xl md:text-4xl mb-4">Witaj na mojej stronie</h2>
      <p class="text-justify md:text-left mb-2">
        Jestem absolwentem dziennych studiów I i II stopnia na Politechnice Warszawskiej z tytułem
        <strong>magistra inżyniera</strong> uzyskanym w październiku 2018r.
      </p>
      <p class="text-justify md:text-left mb-2">
        Ukończyłem <strong>Informatykę na Politechnice Warszawskiej</strong> na kierunku: Java EE –
        produkcja oprogramowania oraz jestem absolwentem studiów podyplomowych z zakresu
        <strong>Frontend Development z React na Akademii Leona Koźmińskiego</strong> w Warszawie.
      </p>
      <p class="text-justify md:text-left mb-2">
        Posiadam wieloletnie doświadczenie w projektowaniu i kodowaniu stron internetowych dla firm,
        osób fizycznych, stron typu landing page, czy serwisów e-commerce.
      </p>
      <AboutMeButton />
    </div>
  </section>
</template>

<style scoped>
.img-animation {
  padding: 8px;
  --border-size: 5px;
  --border-angle: 0turn;
  background-image: conic-gradient(
      from var(--border-angle),
      rgb(255, 255, 255),
      rgb(255, 255, 255) 50%,
      rgb(255, 255, 255)
    ),
    conic-gradient(from var(--border-angle), transparent 20%, #9333ea, #222222);
  background-size:
    calc(100% - var(--border-size) * 2) calc(100% - var(--border-size) * 2),
    cover;
  background-position: center center;
  background-repeat: no-repeat;
  animation: bg-spin 3s linear infinite;
}
@property --border-angle {
  syntax: '<angle>';
  inherits: true;
  initial-value: 0turn;
}
@keyframes bg-spin {
  to {
    --border-angle: 1turn;
  }
}
</style>
