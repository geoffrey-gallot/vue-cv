<template>
  <div class="project">
    <section class="projectPro">
      <article class="weytop projectItem">
        <b-link class="nav-link lien text-secondary text-center" href="https://preprod-admin.weytop.com/">Weytop</b-link>
      </article>
    </section>
    <section class="projectPerso">
      <article class="automaticWatering projectItem">
        <b-link class="nav-link lien text-light text-center" href="https://github.com/geoffrey-gallot/AutomaticWateringV1.2">Arrosage Automatique</b-link>
      </article>
      <article class="siteCV projectItem">
        <b-link class="nav-link lien text-dark text-center" href="https://github.com/geoffrey-gallot/vue-cv">Ce site CV</b-link>
      </article>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Project',
}
</script>

<style scoped>
.fa-plus{
  display: none;
  color: black;
  
}
.projectPerso, .projectPro{
  display: flex;
  flex-direction: row !important;
  margin: 10px;
}
.project{
  position: fixed;
  margin-top: 100px;
  left: 30%;
  display: flex;
  flex-direction: row;
}
.projectItem{
  margin: 20px;
  display: flex;
  flex-direction: column;
}
.lien{
  padding-top: 25%;
  height: 100%;
}
.weytop :hover{
  border-radius: 15px;
  background-color: rgba(0, 0, 0, 0.5);
  
}
.weytop{
  border-radius: 15px;
  width: 160px;
  height: 160px;
  /* height: 100%; */
  background-image: url("../../public/img/resourses/logoWeytopSmall.png");
  background-size: cover 100% 100%;
  background-repeat: no-repeat;
  background-position: center;
}
.automaticWatering{
  border-radius: 15px;
  width: 160px;
  height: 160px;
  /* height: 100%; */
  background-image: url("../../public/img/resourses/photoSitearduino.png");
  background-size: cover 100% 100%;
  background-repeat: no-repeat;
  background-position: center;
}
.automaticWatering :hover{
  border-radius: 15px;
  background-color: rgba(0, 0, 0, 0.5);
}

.siteCV{
  border-radius: 15px;
  width: 160px;
  height: 160px;
  /* height: 100%; */
  background-image: url("../../public/img/icons/android-chrome-192x192.png");
  background-size: cover 100% 100%;
  background-repeat: no-repeat;
  background-position: center;
}
.siteCV :hover{
  border-radius: 15px;
  background-color: rgba(0, 0, 0, 0.5);
}
</style>