<template>
  <nav class="navBar">
    <span class="nav_items">
      <a class="nav_title">Hamza Carew.</a>
      <a> About </a>
      <a> Portfolio </a>
      <a>Contact </a>
    </span>
  </nav>

  <div class="general_section">
      <div class="description">

          <h2 class="description_title">Web Developer, Tech Enthusiast, and Book Worm.</h2>

          <p class="description_text">
             When an unknown printer took a galley of 
                type and scrambled it to make a type specimen book. 
          </p>

          <div class="description_buttons">
              <button class="learnMoreButton"> Learn more </button>
              <button class="getInTouchButton"> Get in touch </button> <!-- push to #contact -->
          </div>
      </div>

       <img class="inner_img" src="/hamza.jpeg" alt="Icon of hamza">
  </div>

  <div class="about_section">
      <h2 class="about_title">About</h2>

      <p class="about_text">
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
          when an unknown printer took a galley of 
          type and scrambled it to make a type specimen book.
      </p>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped>

/* 
- reduce size of title on mobile

*/

.inner_img {
    @apply rounded-full lg:h-56 lg:w-56 h-28 w-28 md:h-48 md:w-48  mt-10 md:mt-6 md:mr-24 order-first md:order-last lg:mr-32;
}

.learnMoreButton {
    @apply text-white bg-black rounded-md font-bold py-2 px-2 mx-4;
}

.getInTouchButton {
    @apply text-black bg-white rounded-md py-2 px-2 border-2 border-black;
}

.description {
    @apply mt-10 w-72;
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

.navBar {
  @apply h-12 shadow-lg text-black;
}

.nav_items {
  @apply flex justify-end space-x-4 py-4 mr-4 md:mr-72 font-bold;
}

.nav_title {
  @apply flex justify-self-start md:w-1/4 mr-32 lg:mr-32 md:mr-80 font-black text-lg md:text-xl;
}

.general_section {
    @apply flex items-center md:flex-row flex-col justify-center md:justify-around text-gray-400 h-96 text-black;
}

.image_container {
    @apply mt-6 mr-8;
}

.about_section {
    @apply bg-black h-80 text-white py-6 mt-10;
}

.about_title {
    @apply font-mono font-bold text-2xl;
}

.about_text {
    @apply font-mono break-words text-lg py-4 px-6 md:px-72 text-center;
}

</style>

