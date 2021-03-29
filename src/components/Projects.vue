<template lang="">
    <div class="projects_section" id="projects">
    <h2 class="projects_title">Projects portal</h2>

    <p class="projects_intro">
      Here is a glimpse of some of the projects I've previously worked on,
      to see more visit my
      <a href="https://github.com/6ixBit" class="bg-purple-400 font-bold"><u>Github.</u>
      </a>
    </p>

       <ul class="icons">
        <img class="fill-current text-white" src="/github.svg" alt="github_icon">
        <!-- <img src="/linkedin.svg" alt="linkedin_icon"> -->
        <img src="/email.svg" alt="email_icon">
      </ul> 

    <!-- Add container of cards, each card represents a project currently up. -->
  </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.icons {
 @apply flex flex-row space-x-4 z-10 fill-current text-white;
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
    