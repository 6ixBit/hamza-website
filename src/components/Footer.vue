<template>
  <footer>
    <div class="footer">
      <p>Copyright 1888 ©</p>

      <ul class="icons">
        <a href="https://github.com/6ixBit">
          <img src="/github.svg" alt="github_icon" />
        </a>
        <a href="https://www.linkedin.com/in/hamza-carew-26b05b159/">
          <img src="/linkedin.svg" alt="linkedin_icon" />
        </a>
        <a href="mailto:h@gmail.com">
          <img src="/email.svg" alt="email_icon" />
        </a>
      </ul>

    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  @apply flex flex-col md:flex-row justify-between items-center bg-black text-white px-16 md:px-28 w-full h-20;
}

p {
  @apply text-base md:text-lg font-bold;
}

.icons {
  @apply flex flex-row pt-2 order-first md:order-last space-x-8 md:space-x-6 z-10 text-white;
}
</style>
