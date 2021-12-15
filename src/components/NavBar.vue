<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top " id="navbar">
      <a class="navbar-brand" tag="router-link" :to="{ path: '/' }">Accueil</a>
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
            <a class="nav-link" href="#">A propos</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Ma formation</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Mes projets</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
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
#navbar{
    text-align: center;
}
</style>
