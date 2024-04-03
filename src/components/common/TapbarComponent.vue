<template>
  <!-- Tapbar -->
  <div
    class="flex items-center justify-around fixed bottom-0 left-0 h-16 w-full bg-purple-600 z-50 md:hidden"
  >
    <RouterLink class="flex flex-col items-center justify-center text-white text-lg" to="/">
      <img
        src="./../../assets/img/tapbar/home.svg"
        alt="Home"
        class="text-xs mb-1 mt-1"
        width="24"
        height="24"
      />
      <span class="text-xs">Home</span>
    </RouterLink>
    <RouterLink class="flex flex-col items-center justify-center text-white text-lg" to="/about-me">
      <img
        src="./../../assets/img/tapbar/about-me.svg"
        alt="O mnie"
        class="text-xs mb-1 mt-1"
        width="24"
        height="24"
      />
      <span class="text-xs">O mnie</span>
    </RouterLink>
    <RouterLink
      class="flex flex-col items-center justify-center text-white text-lg"
      to="/portfolio"
    >
      <img
        src="./../../assets/img/tapbar/portfolio.svg"
        alt="O mnie"
        class="text-xs mb-1 mt-1"
        width="24"
        height="24"
      />
      <span class="text-xs">Portfolio</span>
    </RouterLink>
    <RouterLink
      class="flex flex-col items-center justify-center text-white text-lg"
      to="/references"
    >
      <img
        src="./../../assets/img/tapbar/references.svg"
        alt="O mnie"
        class="text-xs mb-1 mt-1"
        width="24"
        height="24"
      />
      <span class="text-xs">Referencje</span>
    </RouterLink>
    <RouterLink class="flex flex-col items-center justify-center text-white text-lg" to="/contact">
      <img
        src="./../../assets/img/tapbar/contact.svg"
        alt="O mnie"
        class="text-xs mb-1 mt-1"
        width="24"
        height="24"
      />
      <span class="text-xs">Kontakt</span>
    </RouterLink>
  </div>
</template>
