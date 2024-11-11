<script>
</script>

<template>
  <div class="home">
    <Hero />

    <section class="container">
      <Applications />
      <Experience />
    </section>

    <div class="divider bg-secondary">
      <div class="display-4 text-light">SECTION</div>
    </div>

    <section class="container">
      <div class="row my-4">
        <div class="col-lg-6 m-auto ">
          <ContactForm />
        </div>
      </div>
    </section>
  </div>
</template>


<style lang="scss" scoped>
.divider {
  min-height: 24vh;
  margin: 3.5em 0;
  padding: 4em;
  display: flex;
  align-items: center;
}
</style>
