<template>
  <nav class="navBar">
    <span class="nav_items">
      <p class="nav_title">Hamza Carew.</p>
      <a href="#about"> About </a>
      <a href="#projects"> Projects </a>
      <a href="#contact">Contact </a>
    </span>
  </nav>  
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped>

.navBar {
  @apply h-12 shadow-lg text-black sticky;
}

.nav_items {
  @apply flex  justify-end lg:justify-end space-x-4 py-4 mr-4 lg:mr-60 font-bold;
}

.nav_title {
  @apply flex justify-self-start md:w-2/4 md:ml-16 md:mr-28 md:text-xl md:text-lg md:mr-80 lg:mr-4  font-black text-sm mr-8;
}

</style>

