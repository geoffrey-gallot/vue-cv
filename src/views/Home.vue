<template>
  <div class="home">
    <div class="main-content">
      <div class="title">Geoffrey Gallot</div>
      <div class="content">Developpeur Fullstack web et web mobile</div>
      <div class="socialNetwork">
        <ul class="socialNetwork-list">
          <li><a href="https://www.linkedin.com/in/geo-g-1290121aa/"><i class="fab fa-linkedin fa-3x"></i></a></li>
          <li><a href="https://github.com/geoffrey-gallot"><i class="fab fa-github fa-3x"></i></a></li>
          <li><a href="https://www.facebook.com/geoffrey.gallot.9/"><i class="fab fa-facebook fa-3x"></i></a></li>
          <li><a href="https://www.instagram.com/geoffrey.gallot.9/"><i class="fab fa-instagram fa-3x"></i></a></li>
        </ul>      
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  components: {}
};
</script>

<style scoped>
.home{
  position: fixed;
  top: 0;
  height: 100vh;
  width: 100%;
  background-image: url("../../public/img/resourses/pexels-lisa-1048283.jpg");
  background-size: cover;
  z-index: -10;
}
.home img {
  position: fixed;
  top: 0;
  left: 0;
  height: 100vh;
  width: 100%;
  z-index: -100;
}
.main-content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-top: 20%;
}
.title {
  font-size: 3.5rem;
  font-weight: 700;
}
.content {
  font-size: 1.5rem;
  font-weight: 600;
}
.socialNetwork-list{
  display: flex;
  flex-direction: row;
  list-style: none;
  margin-top: 1.5rem;
}
.socialNetwork-list li{
  margin-left: 1rem;
  margin-right: 1rem;
}
.fa-linkedin{
  color: #007BB5;
}
.fa-github{
  color: #6e5494;
}
.fa-facebook{
  color: #4267B2;
}
.fa-instagram{
  color: #F46F30;
}
</style>
