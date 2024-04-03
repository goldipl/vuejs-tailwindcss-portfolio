<template>
  <section class="my-20">
    <div class="projects-container modern-websites pt-24 pb-40 mb-24">
      <h2 class="text-4xl mb-4 text-center">
        Projekty stron w React.js <span class="text-purple-600">|</span> Next.js
        <span class="text-purple-600">|</span> Vue.js
      </h2>
      <p class="text-center">Projekty stron kodowane w oparciu o najnowszy stack technologiczny.</p>
      <p class="text-center">
        W projektach wykorzystuję:
        <strong>React.js, Next.js, Vue.js, TypeScript, styled-components, Tailwind CSS, SCSS</strong
        >.
      </p>
      <div class="wide-wrapper flex flex-wrap justify-center items-center gap-4 my-6">
        <!-- Project -->
        <div class="relative border border-1 border-purple-600">
          <img
            src="./../../assets/img/portfolio/modern_websites/modern_website_01.jpg"
            alt="Travel Website"
            width="410"
            height="205"
            class="h-auto"
          />
          <div
            class="absolute left-0 bottom-0 bg-gradient-to-r from-purple-600 from-45% to-black w-48 p-2 flex justify-around items-center"
          >
            <a
              class="uppercase font-semibold text-white text-sm hover:text-black"
              href="https://goldipl.github.io/travel-website/"
              target="_blank"
              >live</a
            >
            <a
              class="uppercase font-semibold text-white text-sm hover:text-black"
              href="https://github.com/goldipl/travel-website"
              target="_blank"
              >code</a
            >
          </div>
        </div>
        <!-- Project -->
        <div class="relative border border-1 border-purple-600">
          <img
            src="./../../assets/img/portfolio/modern_websites/modern_website_02.jpg"
            alt="Aflux"
            width="410"
            height="205"
            class="h-auto"
          />
          <div
            class="absolute left-0 bottom-0 bg-gradient-to-r from-purple-600 from-45% to-black w-48 p-2 flex justify-around items-center"
          >
            <a
              class="uppercase font-semibold text-white text-sm hover:text-black"
              href="https://goldipl.github.io/aflux-next/"
              target="_blank"
              >live</a
            >
            <a
              class="uppercase font-semibold text-white text-sm hover:text-black"
              href="https://github.com/goldipl/aflux-next"
              target="_blank"
              >code</a
            >
          </div>
        </div>
        <!-- Project -->
        <div class="relative border border-1 border-purple-600">
          <img
            src="./../../assets/img/portfolio/modern_websites/modern_website_03.jpg"
            alt="PhotographersLandingPage"
            width="410"
            height="205"
            class="h-auto"
          />
          <div
            class="absolute left-0 bottom-0 bg-gradient-to-r from-purple-600 from-45% to-black w-48 p-2 flex justify-around items-center"
          >
            <a
              class="uppercase font-semibold text-white text-sm hover:text-black"
              href="https://goldipl.github.io/PhotographersLandingPage/"
              target="_blank"
              >live</a
            >
            <a
              class="uppercase font-semibold text-white text-sm hover:text-black"
              href="https://github.com/goldipl/PhotographersLandingPage"
              target="_blank"
              >code</a
            >
          </div>
        </div>
        <!-- Project -->
        <div class="relative border border-1 border-purple-600">
          <img
            src="./../../assets/img/portfolio/modern_websites/modern_website_04.jpg"
            alt="Self-storage-website"
            width="410"
            height="205"
            class="h-auto"
          />
          <div
            class="absolute left-0 bottom-0 bg-gradient-to-r from-purple-600 from-45% to-black w-48 p-2 flex justify-around items-center"
          >
            <a
              class="uppercase font-semibold text-white text-sm hover:text-black"
              href="https://goldipl.github.io/Self-storage-website/"
              target="_blank"
              >live</a
            >
            <a
              class="uppercase font-semibold text-white text-sm hover:text-black"
              href="https://github.com/goldipl/Self-storage-website"
              target="_blank"
              >code <span class="text-xs lowercase">(in progress)</span></a
            >
          </div>
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
  </section>
</template>

<style scoped>
.projects-container.modern-websites {
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
