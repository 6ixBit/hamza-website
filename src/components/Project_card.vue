<template>
    <div class="card">

        <!-- s -->

        <img src="/futurama.svg" />
       
        <p class="description">
          {{description}}
        </p>        

        <!-- <p class="tech_stack">{{techStack}}</p>     -->
    </div>

</template>

<script>
export default {
    name: "Project_card",
    props: ["name", "description", "techStack"]    
}
</script>

<style scoped>
   .card {
       @apply flex justify-center items-center flex-col rounded-lg 
       h-48  w-80 md:w-96 border-2 font-mono font-black font-bold
       border-black shadow-2xl;
   }

   img {
       @apply w-20 mt-4 mb-4;
   }

   .description {
       @apply font-black text-base;
   }
</style>