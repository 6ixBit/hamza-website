<template lang="">
    <div class="projects_section" id="projects">
    <h2 class="projects_title">Projects portal</h2>

    <p class="projects_intro">
      Lorem Ipsum has been the industry's standard dummy text ever since the
      1500s, when an unknown printer took a galley of type and scrambled it to
      make a type specimen book.
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
    