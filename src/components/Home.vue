<template>
  <NavBar />

  <div class="general_section">
    <div class="description">
      <h2 class="description_title">
        Web Developer, Tech Enthusiast, and Book Worm.
      </h2>

      <p class="description_text">
        When an unknown printer took a galley of type and scrambled it to make a
        type specimen book.
      </p>

      <div class="description_buttons">
        <button class="learnMoreButton">E-mail</button>
        <button class="getInTouchButton">Download CV</button>
        <!-- push to #contact -->
      </div>
    </div>

    <img class="inner_img" src="/hamza.jpeg" alt="Icon of hamza" />
  </div>

  <div class="about_section" id="about">
    <h2 class="about_title">About</h2>

    <p class="about_text">
      Lorem Ipsum has been the industry's standard dummy text ever since the
      1500s, when an unknown printer took a galley of type and scrambled it to
      make a type specimen books.
    </p>
  </div>

  <div class="projects_section" id="projects">
    <h2 class="projects_title">Projects portal</h2>

    <p class="projects_intro">
      Lorem Ipsum has been the industry's standard dummy text ever since the
      1500s, when an unknown printer took a galley of type and scrambled it to
      make a type specimen book.
    </p>

   

    <!-- Add container of cards, each card represents a project currently up. -->
  </div>

  <Footer />
</template>

<script setup>
import NavBar from "./NavBar.vue";
import Footer from "./Footer.vue";
</script>

<style scoped>

/* 
  - make column and set z index ontop of about section
  - add github, linkedin and email svg underneath avatar.
  - add svg icons as stack in about section.
*/

html {
  scroll-behavior: smooth;
}

a:hover {
  text-decoration: underline;
}

.inner_img {
  @apply rounded-full lg:h-56 lg:w-56 h-28 w-28 md:h-48 md:w-48 mt-10 md:mt-6 md:mr-24 order-first md:order-last lg:mr-32;
}

.learnMoreButton {
  @apply text-white bg-black rounded-md font-bold py-2 px-2 mx-4;
}

.getInTouchButton {
  @apply text-black bg-white rounded-md py-2 px-2 border-2 border-black;
}

.image_container {
  @apply mt-6 mr-8;
}

.general_section {
  @apply flex items-center md:flex-row flex-col justify-center md:justify-around text-gray-400 h-96 text-black;
}

.description {
  @apply mt-4 md:mt-10 w-72;
}

.description_title {
  @apply mb-4 font-black text-2xl text-black;
}

.description_buttons {
  @apply mt-6;
}

.description_text {
  @apply text-black text-left;
}

.about_section {
  @apply bg-black h-96 md:h-80  text-white py-6 mt-10;
}

.about_title {
  @apply font-mono font-bold text-2xl;
}

.about_text {
  @apply font-mono break-words text-lg py-4 px-6 lg:px-72 text-center;
}

.projects_section {
  @apply h-96 md:h-80 py-6;
}

.projects_title {
  @apply font-mono text-2xl font-bold;
}

.projects_intro {
  @apply font-mono break-words text-lg py-4 px-6 lg:px-72;
}

</style>
