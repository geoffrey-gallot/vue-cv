<template>
  <div class="contact">
    <section class="coord">
            <Coord/>
    </section>
    <section class="formContact"></section>
  </div>
</template>

<script>
import Coord from '../components/Coord'
export default {
  name: 'Contact',
  components: {
    Coord,
  }
}
</script>

<style scoped>
.contact{
  position: absolute;
  display: flex;
  flex-direction: row;
  width: 100%;
  
}
.coord{
  margin-top: 10%;
  margin-left: 5%;
  width: 150px;
}
</style>