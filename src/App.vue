<script>
</script>

<template>
  <Navbar v-if="!hideNavbar" />

  <main>
    <router-view />
  </main>

  <Foot v-if="!hideFooter" />
</template>

<style lang="scss">
@import "./assets/scss/main.scss";
</style>
