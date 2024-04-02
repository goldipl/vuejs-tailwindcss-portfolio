<script lang="ts">
import type { ComponentOptions } from 'vue'
import AOS from 'aos'
import 'aos/dist/aos.css'

const AOSInitializer: ComponentOptions = {
  mounted() {
    // Initialize AOS when the component is mounted
    AOS.init()
  }
}

export default AOSInitializer
</script>

<template>
  <div class="short-hero-container w-full mt-[-1rem]">
    <div class="relative z-10 flex top-[10vh] justify-center items-center">
      <div
        class="flex flex-col max-w-[640px] 2xl:me-24"
        data-aos="fade-right"
        data-aos-duration="2500"
      >
        <h1
          class="text-5xl bg-gradient-to-r from-purple-600 from-15% to-white bg-clip-text text-transparent font-semibold"
        >
          O mnie
        </h1>
      </div>
    </div>
  </div>
</template>

<style scoped>
.short-hero-container {
  position: relative;
  height: 25vh;
  background-image: linear-gradient(
      to top,
      rgba(0, 255, 247, 0.1294117647) -125%,
      rgba(0, 0, 0, 0.5294117647) 95%
    ),
    url(./../../assets/img/hero/hero.jpg);
  background-position: bottom;
  background-repeat: no-repeat;
  background-size: 600vh;
  background-attachment: fixed;
}
</style>
