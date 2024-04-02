<script lang="ts">
import { defineComponent } from 'vue'
import ReferencesButton from '../buttons/ReferencesButton.vue'

export default defineComponent({
  name: 'ExperienceSection',
  components: {
    ReferencesButton
  }
})
</script>

<template>
  <section id="contact-section" class="wrapper flex flex-col items-center justify-center my-24">
    <h1 class="text-center text-4xl mb-6">Referencje</h1>
    <p>Galeria referencji od osób, z którymi miałem przyjemność współpracować.</p>
    <ReferencesButton />
  </section>
</template>
