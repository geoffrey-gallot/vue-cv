<template>
  <div class="about">
    <div class="main-content">
      <section class="left-content">
        <img src="../../public/img/resourses/photoSite.png" alt="" />
      </section>
      <section class="right-content">
        <article class="about-me">
          <h1>A propos de moi</h1>
          <p>
            Développeur FULL STACK, J'ai profité des deux périodes de
            confinement de 2020 pour commencer à me former au développent web.
            Fort de cet apprentissage en autodidacte, j'ai décidé de faire une
            formation à l'AFPA Territoire digital en télé-présentiel. J'ai, tout
            au long de ma formation, développé plusieurs projets, notamment un
            site web de restaurant (front) et un système d’arrosage automatique
            de potager géré par un Arduino et administré via une interface web.
          </p>
        </article>
        <article class="annexe">
          <div class="contact">
            <Coord />
          </div>
          <div class="cvdl">
            <a
              class="btn btn-secondary"
              href="/dist/img/resourses/CVGallotGeoffrey.pdf"
              target="_blank"
              download
              >Télécharger mon Cv
              </a>
          </div>
        </article>
      </section>
    </div>
  </div>
</template>

<script>
import Coord from "../components/Coord";
export default {
  name: "About",
  components: {
    Coord
  }
};
</script>

<style scoped>
.about {
  position: absolute;
  height: 100vh;
  /* height: 110%; */
  width: 100%;
  background-color: #2b2b2b;
  display: flex;
  flex-direction: row;
  color: #f1f1f1;
}
.main-content {
  width: 100%;
  margin-top: 50px;
  display: flex;
  flex-direction: row;
}
.left-content img {
  height: 170px;
  border-radius: 50%;
  margin-left: 200px;
  margin-right: 100px;
}
.right-content {
  display: flex;
  flex-direction: column;
}
.annexe {
  display: flex;
  flex-direction: row;
  margin-top: 25px;
  margin-right: 20px !important;
}
.about-me {
  margin-right: 300px;
  margin-bottom: 50px;
}
.cvdl {
  margin-left: 200px;
}
@media screen and (max-width: 1000px){
  .about{
    height: auto;
  }
  .main-content{
    position: relative;
    flex-direction: column;
  }
  .right-content{
    flex-direction: column;
    height: 100%;
  }
  .about-me{
    margin-right: 10px;
    margin-left: 10px;
  }
  .annexe{
    flex-direction: column;
    margin-bottom: 10px;
  }
  .left-content img {
    margin-left: 20px;
    margin-right: auto;
  }
  .cvdl{
    margin-left: 32.5%;
  }
}
</style>
