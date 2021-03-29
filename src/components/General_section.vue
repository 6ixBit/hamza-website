<template>
  <div class="general_section">
    <div class="description">
      <h2 class="description_title">
        Web Developer, Tech Enthusiast, and Book Worm.
      </h2>

      <p class="description_text">
        Fascinated by interesting concepts that allow my brain to wander, 
        I spend my time exploring things in tech that I think are cool
      </p>

      <div class="description_buttons">
        <a href="mailto:admin@hamzacarew.com" class="emailButton">E-mail</a>
        <a class="cvButton" href="/HamzaCV.pdf">View CV</a>
      </div>
    </div>

    <img class="inner_img" src="/hamza.jpeg" alt="Icon of hamza" />
  </div>
</template>

<script>
export default {
  name: "General",
};
</script>

<style scoped>
.inner_img {
  @apply rounded-full lg:h-56 lg:w-56 h-28 w-28 md:h-48 md:w-48 mt-10 md:mt-6 md:mr-24 order-first md:order-last lg:mr-32;
}

.emailButton {
  @apply text-white bg-black rounded-md font-bold py-2 px-2 mx-4;
}

.cvButton {
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
</style>
