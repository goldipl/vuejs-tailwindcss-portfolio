<template>
  <section class="mt-20">
    <div class="projects-container figma-projects pt-24 pb-24">
      <h2 class="text-3xl md:text-4xl mb-4 text-center">
        Makiety aplikacji w <span class="text-purple-600">Figma</span>
      </h2>
      <p class="text-center mx-4">
        Projekty aplikacji w jednym z najpopularniejszych narzędzi UX/UI Designera.
      </p>
      <div class="wide-wrapper flex flex-wrap justify-center items-center gap-4 my-6">
        <!-- Project -->
        <div class="relative border border-1 border-purple-600">
          <img
            src="./../../assets/img/portfolio/figma/Figma01.jpg"
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
              href="https://www.figma.com/file/Wfz4cGjEIcJ1dnC9PWU73k/Gotuj-z-pasj%C4%85?node-id=0%3A1"
              target="_blank"
              >live</a
            >
          </div>
        </div>
        <!-- Project -->
        <div class="relative border border-1 border-purple-600">
          <img
            src="./../../assets/img/portfolio/figma/Figma02.jpg"
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
              href="https://www.figma.com/file/fAfesw4O1h4Jhph91UTNzw/Login-Section?node-id=0%3A1"
              target="_blank"
              >live</a
            >
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.projects-container.figma-projects {
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
