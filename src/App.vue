<script setup>
import InfoSection from './components/InfoSection.vue'
import FooterSection from './components/FooterSection.vue'
import FirstSection from './components/FirstSection.vue'
import SecondSection from './components/SecondSection.vue'
import ThirdSection from './components/ThirdSection.vue'
import FourthSection from './components/FourthSection.vue'
</script>

<template>
  <div>
    <main>
      <section class="pt-4 pb-6"><first-section /></section>
      <section class="pt-6 pb-8"><second-section></second-section></section>
      <section class="pb-6"><third-section></third-section></section>
      <section class="pt-6 pb-6"><fourth-section></fourth-section></section>
      <section class="pb-4 pt-6"><info-section /></section>
    </main>
    <footer-section />
  </div>
</template>

<style scoped></style>
