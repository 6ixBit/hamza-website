<template lang="">
   <footer>
    <div class="footer">
      <p>Copyright 1888 ©</p>

      <ul class="icons">
        <img src="/github.svg" alt="github_icon">
        <img src="/linkedin.svg" alt="linkedin_icon">
        <img src="/email.svg" alt="email_icon">
      </ul>
    </div>
  </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped>   

.footer {
  @apply flex justify-between items-center bg-black text-white px-16 md:px-28 bottom-0 left-0 w-full h-16 z-0;
}

p {
    @apply text-lg font-bold;
}

.icons {
 @apply flex flex-row space-x-4 z-10 fill-current text-white;
}
</style>