<template>
  <section id="about-me-section" class="wrapper flex flex-col items-start my-20 md:my-24">
    <div class="flex flex-col justify-center items-center w-full">
      <div class="img-animation w-64 mb-4">
        <img
          src="./../../assets/img/home/about_me/cv-photo.jpg"
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
    <div class="mt-12">
      <h2 class="text-4xl mb-4 text-center">Witaj na stronie "O mnie"</h2>
      <p class="mb-2 text-center">
        Jestem absolwentem dziennych studiów I i II stopnia na Politechnice Warszawskiej z tytułem
        <strong>magistra inżyniera</strong> uzyskanym w październiku 2018r.
      </p>
      <p class="mb-2 text-center">
        Ukończyłem <strong>Informatykę na Politechnice Warszawskiej</strong> na kierunku: Java EE –
        produkcja oprogramowania oraz jestem absolwentem studiów podyplomowych z zakresu
        <strong>Frontend Development z React na Akademii Leona Koźmińskiego</strong> w Warszawie.
      </p>
      <p class="mb-2 text-center">
        Posiadam wieloletnie doświadczenie w projektowaniu i kodowaniu stron internetowych dla firm,
        osób fizycznych, stron typu landing page, czy serwisów e-commerce.
      </p>
      <p class="mb-2 text-center">
        Brałem udział w kodowaniu największych serwisów radiowych i informacyjnych w Polsce, między innymi:
        <ul class="text-center">
          <li><a href="https://www.se.pl/" class="text-sm bg-gradient-to-r from-purple-600 from-25% to-gray-500 bg-clip-text text-transparent font-semibold mt-2 hover:bg-gradient-to-l hover:from-25% hover:from-black hover:to-purple-600">- https://www.se.pl/</a></li>
          <li><a href="https://www.eska.pl/" class="text-sm bg-gradient-to-r from-purple-600 from-25% to-gray-500 bg-clip-text text-transparent font-semibold mt-2 hover:bg-gradient-to-l hover:from-25% hover:from-black hover:to-purple-600">- https://www.eska.pl/</a></li>
          <li><a href="https://www.voxfm.pl/" class="text-sm bg-gradient-to-r from-purple-600 from-25% to-gray-500 bg-clip-text text-transparent font-semibold mt-2 hover:bg-gradient-to-l hover:from-25% hover:from-black hover:to-purple-600">- https://www.voxfm.pl/</a></li>
          <li><a href="https://muratordom.pl/" class="text-sm bg-gradient-to-r from-purple-600 from-25% to-gray-500 bg-clip-text text-transparent font-semibold mt-2 hover:bg-gradient-to-l hover:from-25% hover:from-black hover:to-purple-600">- https://muratordom.pl/</a></li>
        </ul>
      </p>
      <p class="mb-2 mt-4 text-center">
        czy też jednego z największych przedstawicieli e-commerce w zakresie branży projektów budowlanych:
        <ul class="text-center">
          <li><a href="https://projekty.muratordom.pl/" class="underline text-sm bg-gradient-to-r from-purple-600 from-25% to-gray-500 bg-clip-text text-transparent font-semibold mt-2 hover:bg-gradient-to-l hover:from-25% hover:from-black hover:to-purple-600">- https://projekty.muratordom.pl/</a></li>
        </ul>
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
