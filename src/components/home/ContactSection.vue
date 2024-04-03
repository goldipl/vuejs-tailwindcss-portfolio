<script lang="ts">
import { defineComponent } from 'vue'
import ContactButton from '../buttons/ContactButton.vue'

export default defineComponent({
  name: 'ExperienceSection',
  components: {
    ContactButton
  }
})
</script>

<template>
  <section
    id="contact-section"
    class="wrapper flex flex-col items-center justify-center my-12 md:my-24"
  >
    <h1 class="text-center text-3xl md:text-4xl mb-6">Kontakt</h1>
    <p>Podobają Ci się moje prace?</p>
    <p>Zapraszam do kontaktu, zróbmy coś razem!</p>
    <ContactButton />
  </section>
</template>
