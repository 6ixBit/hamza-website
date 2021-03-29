<template lang="">
   <footer>
    <div class="footer">
      <p>GitHub</p>

      <ul class="icons">
        <a href="">Telegram</a>
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
  @apply flex justify-between items-center bg-black text-white px-16 bottom-0 left-0 w-full h-16;
}
</style>