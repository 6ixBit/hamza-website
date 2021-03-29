vue
<template lang="">
  <div class="about_section" id="about"> <h2 class="about_title">About</h2> <p
  class="about_text"> Lorem Ipsum has been the industry's standard dummy text
  ever since the 1500s, when an unknown printer took a galley of type and
  scrambled it to make a type specimen books. </p> </div>
</template>

<script>
export default {
    name: "About"
};
</script>

<style scoped> 
.about_section {
  @apply bg-black h-96 md:h-80  text-white py-6 mt-10;
}

.about_title {
  @apply font-mono font-bold text-2xl;
}

.about_text {
  @apply font-mono break-words text-lg py-4 px-6 lg:px-72 text-center;
}
</style>
