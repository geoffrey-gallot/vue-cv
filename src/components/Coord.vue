<template>
  <div class="contact">
    <h4>Contact :</h4>
    <ul>
      <li>Geoffrey Gallot</li>
      <li>19 rue des colporteurs</li>
      <li>Villebreton</li>
      <li>16110 la Rochette</li>
      <li>E-mail : <b-link href="mailto:geoffrey.gallot@gmail.com<">geoffrey.gallot@gmail.com</b-link></li>
      <li>Tel : 06 41 71 52 18</li>
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
  width: 250px;
}
.contact ul {
  list-style: none;
  white-space: nowrap;
}
.contact ul li{
    margin-top: 10px;
}
</style>
