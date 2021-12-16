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
  position: fixed;
  top: 100px;
  display: flex;
  flex-direction: column;
  margin-left: 100px;
}
</style>