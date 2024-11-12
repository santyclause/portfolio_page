<script>

</script>

<template>
  <div class="container">
    <section class="row">
      <div class="col-6">
        <div class="d-flex app-card">
          <div class="w-50">
            <img src="../assets/img/pocket-ranger.png" alt="Pocket Ranger" class="app-img">
          </div>
          <div class="w-50 app-details bg-danger">
            <h4 class="text-center">Pocket Ranger</h4>
            <p>All you need hub for national parks!</p>
            <p>Browse parks, things to do, weather info, articles, alerts, and more.</p>
            <button>View it Live!</button>
          </div>
          <div class="tech-info">
            <h4>Primary Technologies Used</h4>
            <ul>
              <li>Vue.js, Node.js</li>
              <li>MongoDB, Mongoose, ExpressJS</li>
              <li>National Parks Service API</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="col-6">
        <div class="d-flex app-card">
          <div class="w-50 bg-success">
            <img src="" alt="">
          </div>
          <div class="w-50 app-details bg-danger">
            <h4>Keepr</h4>
            <p>View user posted images, save them to albums, and post your own images.</p>
            <button>View it Live!</button>
          </div>
          <div class="tech-info">
            <h4>Primary Technologies Used</h4>
            <ul>
              <li>Vue.js, Node.js</li>
              <li>C#, MySQL</li>
              <li>HTML, CSS, Javascript</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="col-6">
        <div class="d-flex app-card">
          <div class="w-50 bg-success">
            <img src="" alt="">
          </div>
          <div class="w-50 app-details bg-danger">
            <h4>Moon Miner</h4>
            <p>Description</p>
            <button>View it Live!</button>
          </div>
          <div class="tech-info">
            <h4>Primary Technologies Used</h4>
            <ul>
              <li>Vue.js</li>
              <li>C#, MySQL</li>
              <li>Other stuff idk</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="col-6">
        <div class="d-flex app-card">
          <div class="w-50 bg-success">
            <img src="" alt="">
          </div>
          <div class="w-50 app-details bg-danger">
            <h4>Mod</h4>
            <p>Description</p>
            <button>View it Live!</button>
          </div>
          <div class="tech-info">
            <h4>Primary Technologies Used</h4>
            <ul>
              <li>Vue.js</li>
              <li>C#, MySQL</li>
              <li>Other stuff idk</li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
.app-card {
  position: relative;
  height: 40vh;
  margin-top: 1em;
  margin-bottom: 100px;
}

.app-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: left;
}

.app-details {
  padding: 0.5em 1em;
}

.tech-info {
  position: absolute;
  width: 75%;
  height: 150px;
  padding: 0.5em 1em;
  background-color: var(--bs-dark);
  color: var(--bs-primary);
  bottom: -100px;
  left: 12.5%;
}
</style>
