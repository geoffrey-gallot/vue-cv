<template>
  <div>
    <nav
      class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top textCenter">
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <b-link class="nav-link" :to="{ path: '/' }">Accueil</b-link>
          </li>
          <li class="nav-item">
            <b-link class="nav-link" :to="{ path: '/about' }">A propos</b-link>
          </li>
          <li class="nav-item">
            <b-link class="nav-link" :to="{ path: '/formation' }"
              >Ma formation</b-link
            >
          </li>
          <li class="nav-item">
            <b-link class="nav-link" :to="{ path: '/project' }"
              >Mes projets</b-link
            >
          </li>
          <li class="nav-item">
            <b-link class="nav-link" :to="{ path: '/contact' }">Contact</b-link>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "NavBar"
};
</script>

<style scoped>
.textCenter {
  display: flex;
  flex-direction: column;
  text-align: center;
}
</style>
