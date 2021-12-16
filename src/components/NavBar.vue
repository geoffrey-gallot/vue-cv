<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="dark">
      <b-navbar-brand :to="{ path: '/' }">Accueil</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-link class="nav-link" :to="{ path: '/about' }">A propos</b-link>
          <b-link class="nav-link" :to="{ path: '/formation' }"
            >Ma formation</b-link>
          <b-link class="nav-link" :to="{ path: '/project' }"
            >Mes projets</b-link>
          <b-link class="nav-link" :to="{ path: '/contact' }">Contact</b-link>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "NavBar"
};
</script>

<style scoped>
</style>
