<script>
</script>

<template>
  <div class="home">
    <Hero />

    <section class="container">
      <Applications />
    </section>

    <div class="divider mb-5 mt-3 bg-dark">
      <h1 class="text-primary">My Experience</h1>
    </div>

    <section class="container-fluid">
      <Experience />
    </section>

    <div class="divider bg-dark">
      <div class="text-primary">
        <h1>Contact Me</h1>
      </div>
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
