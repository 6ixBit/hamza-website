<template>
  <NavBar />
  <General_section />
  <About />
  <Projects />
  <Footer />
</template>

<script setup>
import NavBar from "./NavBar.vue";
import Footer from "./Footer.vue";
import Projects from "./Projects.vue";
import About from "./About.vue";
import General_section from "./General_section.vue";
</script>

<style>
/* 
  - make column and set z index ontop of about section
  - add github, linkedin and email svg underneath avatar.
  - add svg icons as stack in about section.
*/
html {
  scroll-behavior: smooth;
}

body {
  height: 100vh;
}
</style>
