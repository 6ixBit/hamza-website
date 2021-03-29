<template lang="">
  <div class="about_section" id="about"> 
    <h2 class="about_title">About</h2> 
  <p class="about_text"> 
  I'm Hamza. I'm a full stack developer who enjoys working with modern technology 
  on both sides of the stack. I initially started out doing Cyber security at the start of my degree but 
  got into programming outside of class and eventually ended up switching to BSc Computer Science in which I
  graduated with a First Class Honors in 2020.
  </p>

  <ul class="stack_icons">
    <img src="/golang.svg" alt="golang icon">
    <img src="/python.svg" alt="python icon"/>
    <img src="/js.svg" alt="javascript_icon"/>
    <img src="/vue.svg" alt="vue icon"/>
    <img src="/docker.svg" alt="docker icon"/>
    <img src="/kubernetes.svg" alt="kubernetes icon"/>
    <img src="/firestore.svg" alt="firestore icon"/>
  </ul>
  </div>
</template>

<script>
export default {
  name: "About",
};
</script>

<style scoped>
.about_section {
  @apply bg-black md:h-80  text-white py-6 mt-10;
  height: 25rem;
}

.about_title {
  @apply font-mono font-bold text-2xl;
}

.about_text {
  @apply font-mono break-words text-sm md:text-lg py-1 md:py-4 px-6 lg:px-72 text-center;
}

.stack_icons {
  @apply flex flex-wrap md:w-full md:flex-nowrap justify-center flex-row space-x-4 mt-6 md:mt-4 md:mb-8;
}
</style>
