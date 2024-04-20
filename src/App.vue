<script setup>
import NavbarVue from './components/base/Navbar.vue';
import HeroesVue from './components/view/Heroes.vue';
import ProgramVue from './components/view/Program.vue';
import GaleryVue from './components/view/Galery.vue';
import AboutVue from './components/view/About.vue';
import FooterVue from './components/base/footer.vue';
</script>

<template>
  <nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-primary shadow-sm">
    <NavbarVue />
  </nav>
  <section id="heroes">
    <HeroesVue />
  </section>
  <section id="program">
    <ProgramVue />
  </section>
  <section id="galery">
    <GaleryVue />
  </section>
  <section id="about">
    <AboutVue />
  </section>
  <footer class="shadow-sm bg-primary">
    <FooterVue />
  </footer>
</template>
