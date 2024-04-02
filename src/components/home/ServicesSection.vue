<template>
  <section id="services-section" class="pt-40 pb-64">
    <div class="wrapper">
      <h2 class="text-center text-4xl mb-8">Usługi</h2>
      <h3 class="text-center mb-5">Oferowane przeze mnie usługi zapewniają:</h3>
      <div class="flex flex-row items-start justify-center">
        <div
          class="flex flex-col items-center justify-center max-w-[300px] px-16 m-4 border border-1 rounded-xl border-gray-400 min-h-80 hover:border-purple-600 transition-all duration-500"
        >
          <img
            src="./../../assets/img/home/services/services_seo.svg"
            alt="Pozycjonowanie stron internetowych"
            width="100"
            height="100"
          />
          <strong class="text-center uppercase my-4">seo</strong>
          <p class="text-center text-sm">Pozycjonowanie stron internetowych</p>
        </div>
        <div
          class="flex flex-col items-center justify-center max-w-[300px] px-16 m-4 border border-1 rounded-xl border-gray-400 min-h-80 hover:border-purple-600 transition-all duration-500"
        >
          <img
            src="./../../assets/img/home/services/services_clean_code.svg"
            alt="Projektowanie i programowanie stron internetowych z dbałością o szczegóły"
            width="100"
            height="100"
          />
          <strong class="text-center uppercase my-4">czysty kod</strong>
          <p class="text-center text-sm">
            Projektowanie i programowanie stron internetowych z dbałością o szczegóły
          </p>
        </div>
        <div
          class="flex flex-col items-center justify-center max-w-[300px] px-16 m-4 border border-1 rounded-xl border-gray-400 min-h-80 hover:border-purple-600 transition-all duration-500"
        >
          <img
            src="./../../assets/img/home/services/services_on_time.svg"
            alt="Projekty realizowane zawsze na czas"
            width="100"
            height="100"
          />
          <strong class="text-center uppercase my-4">100% zadowolenia</strong>
          <p class="text-center text-sm">Projekty realizowane zawsze na czas</p>
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
  </section>
</template>

<style scoped>
#services-section {
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
