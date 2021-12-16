<template>
  <div class="contact">
    <h4>Contact :</h4>
    <ul>
      <li>Geoffrey Gallot</li>
      <li>19 rue des colporteurs</li>
      <li>Villebreton</li>
      <li>16110 la Rochette</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Coord"
};
</script>

<style scoped>
.contact {
  display: flex;
  flex-direction: column;
}
.contact ul {
  list-style: none;
}
.contact ul li{
    margin-top: 10px;
}
</style>
