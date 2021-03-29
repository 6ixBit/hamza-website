<template>
  <nav class="navBar">
    <span class="nav_items">
      <p class="nav_title">Hamza Carew.</p>
      <a href="#about"> About </a>
      <a href="#projects"> Projects </a>
      <a href="#contact">Contact </a>
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

  <div class="about_section" id="about">
      <h2 class="about_title">About</h2>

      <p class="about_text">
          Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
          when an unknown printer took a galley of 
          type and scrambled it to make a type specimen book.
      </p>
  </div>

    <div class="projects_section" id="projects">
        <h2 class="projects_title">Projects portal</h2>

        <p class="projects_intro">
            Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
            when an unknown printer took a galley of 
            type and scrambled it to make a type specimen book.
        </p>

        <!-- Add container of cards, each card represents a project currently up. -->
    </div>

    <footer>
        <div class="footer">
            <p>GitHub </p>

            <ul class="icons">
                <a href="">Telegram</a>
            </ul>
        </div>
    </footer>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped>

/* 
- make column and set z index ontop of about section
- add white background for third section of page
- add github, linkedin and email svg underneath avatar.
- add svg icons as stack in about section.

- forgot that I stupidly coded the entire frontend webpage in one component, lmao.

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

.navBar {
  @apply h-12 shadow-lg text-black sticky;
}

.nav_items {
  @apply flex  justify-end lg:justify-end space-x-4 py-4 mr-4 lg:mr-60 font-bold;
}

.nav_title {
  @apply flex justify-self-start md:w-2/4 md:ml-16 md:mr-28 md:text-xl md:text-lg md:mr-80 lg:mr-4  font-black text-sm mr-8;
}

.general_section {
    @apply flex items-center md:flex-row flex-col justify-center md:justify-around text-gray-400 h-96 text-black;
}

.image_container {
    @apply mt-6 mr-8;
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

.footer {
    @apply flex justify-between items-center bg-black text-white px-6 bottom-0 left-0 w-full h-16;
}

</style>

