<template lang="">
  <div class="projects_section" id="projects">
    <h2 class="projects_title">Projects portal</h2>

    <p class="projects_intro">
      Here is a glimpse of some of the projects I've previously worked on,
      to see more visit my
      <a href="https://github.com/6ixBit" class="bg-purple-400 font-bold"><u>Github.</u></a>
    </p>

    <div class="cards">
      <ProjectCard name="xStat" description="I said let me" techStack="Python"/>
    </div>
  </div>
</template>

<script>
import ProjectCard from "./Project_card.vue"

export default {
    name: "Projects",
    components: {
      ProjectCard
    }
}
</script>

<style scoped>
.cards {
  @apply flex justify-center my-8;
}

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
    