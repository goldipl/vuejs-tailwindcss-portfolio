<template>
  <section id="about-me-section" class="wrapper flex flex-row items-start my-24">
    <div>
      <div class="img-animation w-64 mb-4">
        <img
          src="./../../assets/img/home/cv-photo.jpg"
          alt="Zdjęcie profilowe"
          width="300"
          height="300"
        />
      </div>
      <div class="flex flex-col items-center">
        <p class="text-center">Front-end Developer</p>
        <strong class="inline-flex text-center">mgr inż. Marcin Godlewski</strong>
      </div>
    </div>
    <div class="ms-8 mt-12">
      <h2 class="text-4xl mb-4">Witaj na mojej stronie</h2>
      <p class="mb-2">
        Jestem absolwentem dziennych studiów I i II stopnia na Politechnice Warszawskiej z tytułem
        <strong>magistra inżyniera</strong> uzyskanym w październiku 2018r.
      </p>
      <p class="mb-2">
        Ukończyłem <strong>Informatykę na Politechnice Warszawskiej</strong> na kierunku: Java EE –
        produkcja oprogramowania oraz jestem absolwentem studiów podyplomowych z zakresu
        <strong>Frontend Development z React na Akademii Leona Koźmińskiego</strong> w Warszawie.
      </p>
      <p class="mb-2">
        Posiadam wieloletnie doświadczenie w projektowaniu i kodowaniu stron internetowych dla firm,
        osób fizycznych, stron typu landing page, czy serwisów e-commerce.
      </p>
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
