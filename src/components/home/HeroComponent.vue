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
  <div class="hero-container w-full mt-[-1rem]">
    <div class="relative z-10 flex top-[10vh] justify-center items-center">
      <div
        class="flex flex-col max-w-[640px] 2xl:me-24"
        data-aos="fade-right"
        data-aos-duration="1500"
      >
        <h1 class="text-5xl mb-4">
          Tworzę
          <span
            class="bg-gradient-to-r from-purple-600 from-15% to-white bg-clip-text text-transparent font-semibold"
            >unikatowe</span
          ><br />serwisy internetowe
        </h1>
        <p class="text-sm max-w-[480px]">
          Jestem Front-end Developerem z ponad 3 letnim doświadczeniem w kodowaniu stron
          internetowych, landing page, serwisów e-commerce.
        </p>
        <div class="my-7">
          <a
            class="text-gray-300 text-sm hover:text-white px-4 py-3 me-4 border hover:border-purple-600 transition-all duration-500"
            href="#about-me-section"
            >Dowiedz się więcej</a
          >
          <RouterLink
            class="text-gray-300 text-sm hover:text-white px-4 py-3 border hover:border-purple-600 transition-all duration-500"
            to="/portfolio"
            >Moje projekty</RouterLink
          >
        </div>
      </div>
      <div class="flex" data-aos="fade-left" data-aos-duration="1500">
        <img src="./../../assets/img/hero/frontend-icons.svg" alt="Frontend Icons" />
      </div>
    </div>
    <div class="white-shape">
      <svg
        class="mx-auto invert rotate-180 absolute left-0 w-1/2 bottom-0 h-40"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 1000 100"
        preserveAspectRatio="none"
      >
        <path
          class="elementor-shape-fill"
          d="M421.9,6.5c22.6-2.5,51.5,0.4,75.5,5.3c23.6,4.9,70.9,23.5,100.5,35.7c75.8,32.2,133.7,44.5,192.6,49.7
        c23.6,2.1,48.7,3.5,103.4-2.5c54.7-6,106.2-25.6,106.2-25.6V0H0v30.3c0,0,72,32.6,158.4,30.5c39.2-0.7,92.8-6.7,134-22.4
        c21.2-8.1,52.2-18.2,79.7-24.2C399.3,7.9,411.6,7.5,421.9,6.5z"
        ></path>
      </svg>
    </div>
  </div>
</template>

<style scoped>
.hero-container {
  position: relative;
  height: 85vh;
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
