<template>
    <div class="card">
        
        <h1>{{name}}</h1> 
        {{description}}
        {{techStack}}
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
       @apply flex justify-center rounded-lg 
       h-48 w-96 border-2 
       border-transparent shadow-lg my-8;
   }
</style>