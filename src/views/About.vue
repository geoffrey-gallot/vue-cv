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
            <h4>Contact</h4>
            <ul>
              <li>Geoffrey Gallot</li>
              <li>19 rue des colporteurs</li>
              <li>Villebreton</li>
              <li>16110 la Rochette</li>
            </ul>
          </div>
          <div class="cvdl">
            <input
              type="button"
              class="btn btn-secondary"
              download="../../public/img/resourses/CVGallotGeoffrey.pdf"
              value="Télécharger mon Cv"
            />
          </div>
        </article>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "About"
};
</script>

<style scoped>
.about {
  height: 93vh;
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
}
.about-me {
  margin-right: 300px;
  margin-bottom: 50px;
}
.contact {
  margin-right: 150px;
}
.contact ul {
  list-style: none;
}
.cvdl {
}
</style>
