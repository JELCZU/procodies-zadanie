<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import FormSection from './components/FormSection.vue'
import InfoSection from './components/InfoSection.vue'
import FooterSection from './components/FooterSection.vue'
import FirstSection from './components/FirstSection.vue'
import SecondSection from './components/SecondSection.vue'
import ThirdSection from './components/ThirdSection.vue'
import FourthSection from './components/FourthSection.vue'
</script>

<template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header> -->

  <main>
    <!-- <section><form-section></form-section></section> -->
    <section><first-section /></section>
    <section><second-section></second-section></section>
    <section><third-section></third-section></section>
    <section><fourth-section></fourth-section></section>
    <section><info-section /></section>
    <!-- <TheWelcome /> -->
  </main>
  <footer-section />
</template>

<style scoped></style>
