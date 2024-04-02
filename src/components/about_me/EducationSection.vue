<template>
  <section id="education-section" class="pt-36 pb-48">
    <div class="wrapper">
      <h1 class="text-center text-4xl mb-10">Wykształcenie</h1>
      <!-- Education slot -->
      <div class="my-6">
        <p class="text-center">10/2021 – 06/2022</p>
        <p
          class="my-0.5 text-lg text-center bg-gradient-to-r from-purple-600 from-15% to-white bg-clip-text text-transparent font-semibold"
        >
          Akademia Leona Koźmińskiego
        </p>
        <p class="text-center">kierunek: Informatyka</p>
        <p class="text-center">studia podyplomowe: Frontend Development z React</p>
      </div>
      <!-- Education slot -->
      <div class="my-6">
        <p class="text-center">10/2019 – 09/2020</p>
        <p
          class="my-0.5 text-lg text-center bg-gradient-to-r from-purple-600 from-15% to-white bg-clip-text text-transparent font-semibold"
        >
          Politechnika Warszawska
        </p>
        <p class="text-center">Wydział Elektroniki i Technik Informacyjnych</p>
        <p class="text-center">kierunek: Informatyka</p>
        <p class="text-center">studia podyplomowe: Java EE – produkcja oprogramowania</p>
      </div>
      <!-- Education slot -->
      <div class="my-6">
        <p class="text-center">10/2012 – 10/2018</p>
        <p
          class="my-0.5 text-lg text-center bg-gradient-to-r from-purple-600 from-15% to-white bg-clip-text text-transparent font-semibold"
        >
          Politechnika Warszawska
        </p>
        <p class="text-center">
          Wydział Instalacji Budowlanych, Hydrotechniki i Inżynierii Środowiska
        </p>
        <p class="text-center">
          kierunek: Inżynieria Środowiska (studia stacjonarne I i II stopnia)
        </p>
        <p class="text-center">specjalność: Inżynieria Sanitarna i Wodna oraz ZwWiOŚ</p>
      </div>
      <!-- Education slot -->
      <div class="my-6">
        <p class="text-center">09/2009 – 04/2011</p>
        <p
          class="my-0.5 text-lg text-center bg-gradient-to-r from-purple-600 from-15% to-white bg-clip-text text-transparent font-semibold"
        >
          XXI L.O. im. Hugona Kołłątaja w Warszawie
        </p>
        <p class="text-center">profil: matematyczno-informatyczny</p>
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
#education-section {
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
