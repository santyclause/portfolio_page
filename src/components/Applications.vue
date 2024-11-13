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
          <div class="w-50 app-details">
            <div>
              <h4 class="text-center">Pocket Ranger</h4>
              <p>All you need hub for national parks!</p>
              <p>Browse parks, things to do, weather info, articles, alerts, and more.</p>
            </div>
            <div>
              <button class="app-btn selectable">View it Live!</button>
            </div>
          </div>
          <div class="container-fluid tech-info">
            <h4>Primary Technologies Used</h4>
            <section class="row align-items-center">
              <div class="col-2 d-flex justify-content-end fs-4"><i class="mdi mdi-monitor-cellphone"></i></div>
              <div class="col-10 text-light">
                <span>Vue.js, Node.js</span>
              </div>
              <div class="col-2 d-flex justify-content-end fs-4"><i class="mdi mdi-database-outline"></i></div>
              <div class="col-10 text-light">
                <span>MongoDB, Mongoose, ExpressJS</span>
              </div>
              <div class="col-2 d-flex justify-content-end fs-4"><i class="mdi mdi-map"></i></div>
              <div class="col-10 text-light">
                <span>National Parks Service API, HERE Maps API</span>
              </div>
            </section>
          </div>
        </div>
      </div>
      <div class="col-6">
        <div class="d-flex app-card">
          <div class="w-50">
            <img src="" alt="">
          </div>
          <div class="w-50 app-details">
            <div>
              <h4 class="text-center">Keepr</h4>
              <p>View user posted images, save them to albums, and post your own images.</p>
            </div>
            <div>
              <button class="app-btn selectable">View it Live!</button>
            </div>
          </div>
          <div class="tech-info">
            <h4>Primary Technologies Used</h4>
            <section class="row align-items-center">
              <div class="col-2 d-flex justify-content-end fs-4"><i class="mdi mdi-monitor-cellphone"></i></div>
              <div class="col-10 text-light">
                <span>Vue.js, Node.js</span>
              </div>
              <div class="col-2 d-flex justify-content-end fs-4"><i class="mdi mdi-database-outline"></i></div>
              <div class="col-10 text-light">
                <span>C#, MySQL</span>
              </div>
              <div class="col-2 d-flex justify-content-end fs-4"><i class="mdi mdi-language-html5"></i></div>
              <div class="col-10 text-light">
                <span>HTML, CSS, Javascript</span>
              </div>
            </section>
          </div>
        </div>
      </div>
      <div class="col-6">
        <div class="d-flex app-card">
          <div class="w-50">
            <img src="" alt="">
          </div>
          <div class="w-50 app-details">
            <div>
              <h4 class="text-center">Moon Miner</h4>
              <p>Description</p>
            </div>
            <div>
              <button class="app-btn selectable">View it Live!</button>
            </div>
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
          <div class="w-50">
            <img src="" alt="">
          </div>
          <div class="w-50 app-details">
            <div>
              <h4 class="text-center">Mod</h4>
              <p>Description</p>
            </div>
            <div>
              <button class="app-btn selectable">View it Live!</button>
            </div>
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
  border: 2px solid var(--bs-dark);
  box-shadow: 2px 2px 5px var(--bs-dark)
}

.app-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: left;
}

.app-details {
  padding: 0.5em 1em 66px 1em;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
}

.app-btn {
  background-color: unset;
  font-weight: 600;
  border: none;
  border-bottom: 2px solid var(--bs-primary);
}

.tech-info {
  position: absolute;
  width: 75%;
  min-height: 162px;
  padding: 0.5em 1em;
  background: linear-gradient(0, var(--bs-dark), #333333);
  color: var(--bs-primary);
  bottom: -100px;
  left: 12.5%;
  border-radius: 20px;
}
</style>
