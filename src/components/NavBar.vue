<template>
  <nav class="navBar">
    <span class="nav_items">
        <div class="nav_title">
            <a>Hamza C.</a>
        </div>
      <a> About </a>
      <a> Portfolio </a>
      <a>Contact </a>
    </span>
  </nav>

  <div class="general_section">
      general...
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
.navBar {
  @apply bg-gray-300 h-12 shadow-xl;
}

.nav_items {
  @apply flex justify-end space-x-4 py-4 mr-4 md:mr-72 font-bold;
}

.nav_title {
  @apply flex justify-self-start mr-9 md:mr-96 w-1/5 font-black text-xl;
}

.general_section {
    @apply text-gray-400 h-96 text-black;
}

.about_section {
    @apply bg-black h-80 text-white py-6 mt-10;
}

.about_title {
    @apply font-mono font-bold text-2xl;
}

.about_text {
    @apply font-mono break-words text-lg py-6 px-6 md:px-72 text-center;
}

</style>
