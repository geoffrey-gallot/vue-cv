<template>
  <div class="formation">
    <section class="main-section education">
      <article class="title"><h3>Formation:</h3></article>
      <article class="content">
        <h4>D2WM</h4>
        <h5>titre profesionnel de niveau 5 (BTS/DUT)</h5>
        <p>
          Formation developpeur web et web mobile à l'AFPA territoir digital du
          30 novembre 2020 au 6 octobre 2021
        </p>
        <p>
          - Développer la partie front-end d’une application web ou web mobile
          en intégrant les recommandations de sécurité. <br />
          - Développer la partie back-end d’une application web ou web mobile en
          intégrant les recommandations de sécurité.
        </p>
      </article>
    </section>
    <section class="main-section experience">
      <article class="title"><h3>Experiences:</h3></article>
      <article class="content">
        <h4>Stage Weytop</h4>
        <h5>Du 5 juillet 2021 au 26 septembre 2021</h5>
        <p>
          - Développer le nouveaux site corporate de la société en respectant la
          maquette fournis et la feuille de style existante avec le framework
          php Slim.

          <br />
          - Aider a l'integration du module de paiement stripe dans l
          architecture existante.
        </p>
      </article>
    </section>
    <section class="main-section skills">
      <article class="title"><h3>Compétences:</h3></article>
      <article class="content skill-list">
        <ul>
          <li>
            <h5>HTML/CSS</h5>
            <b-progress
              :value="80"
              :max="100"
              class="mb-3"
              variant="secondary"
            ></b-progress>
          </li>
          <li>
            <h5>PHP/MySQL</h5>
            <b-progress
              :value="70"
              :max="100"
              class="mb-3"
              variant="secondary"
            ></b-progress>
          </li>
          <li>
            <h5>JS/JQuery</h5>
            <b-progress
              :value="75"
              :max="100"
              class="mb-3"
              variant="secondary"
            ></b-progress>
          </li>
        </ul>
        <ul>
          <li>
            <h5>Symfony</h5>
            <b-progress
              :value="60"
              :max="100"
              class="mb-3"
              variant="secondary"
            ></b-progress>
          </li>
          <li>
            <h5>Bootstrap/Bulma</h5>
            <b-progress
              :value="85"
              :max="100"
              class="mb-3"
              variant="secondary"
            ></b-progress>
          </li>
          <li>
            <h5>Vue.js</h5>
            <b-progress
              :value="65"
              :max="100"
              class="mb-3"
              variant="secondary"
            ></b-progress>
          </li>
        </ul>
      </article>
    </section>
  </div>
</template>

<script>
export default {
  name: "Formation"
};
</script>

<style scoped>
.formation {
  display: flex;
  flex-direction: column;
}
.main-section {
  margin-top: 100px;
  display: flex;
  flex-direction: row;
}
.title {
  text-decoration: underline;
  width: 300px;
  padding-left: 50px;
}
.content {
  margin-top: 5px;
}
.skill-list {
  display: flex;
  flex-direction: row;
}
.skill-list ul {
  list-style: none;
  width: 450px;
}
</style>
