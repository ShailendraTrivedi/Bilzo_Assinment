<script setup>
import Navbar_Component from './components/Navbar.vue'
import FirstSection from './components/FirstSection.vue'
import SecondSection from "./components/SecondSection.vue"
import ThirdSection from "./components/ThirdSection.vue"
import FourthSection from "./components/FourthSection.vue"
import FifthSection from "./components/FifthSection.vue"
import SixthSection from "./components/SixthSection.vue"
import Footer_Component from "./components/Footer.vue"
</script>

<template>
  <Navbar_Component />
  <FirstSection />
  <SecondSection />
  <div class="line">
  </div>
  <ThirdSection />
  <FourthSection />
  <div class="fifth_section">
    <FifthSection />
    <SixthSection />
  </div>
  <Footer_Component />
</template>

<style scoped>
@media screen and (max-width: 400px) {
  .line {
    width: 312px;
    height: 2px;
    background: #ced4dc;
    flex: none;
    order: 0;
    align-self: stretch;
    flex-grow: 0;
    margin: 50px auto;
  }

  .fifth_section {
    display: none;
  }

}
</style>