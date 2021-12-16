<template>
  <div class="about">
    <div class="main-content">
      <section class="left-content">
        <img src="../../public/img/resourses/photoSite.png" alt="">
      </section>
      <section class="right-content">
        <article class="about-me">
          <h1>A propos de moi</h1>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque, provident!
          Corporis maiores nesciunt consequuntur, nam a veritatis veniam ipsa? Explicabo?
          Ducimus atque, eos perspiciatis nostrum temporibus saepe rem eius aliquid?
          Tempore totam asperiores quod aliquid accusantium voluptatum qui reiciendis earum.
          Saepe aperiam magnam nisi reprehenderit autem adipisci expedita quasi eius?</p>
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
            <input type="button" class="btn btn-secondary" download="../../public/img/resourses/CVGallotGeoffrey.pdf" value="Télécharger mon Cv">
          </div>
        </article>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: 'About',
}
</script>

<style scoped>
.about{
  height: 93vh;
  width: 100%;
  background-color: #2B2B2B;
  display: flex;
  flex-direction: row;
  color: #f1f1f1;
}
.main-content{
  width: 100%;
  margin-top: 50px;
  display: flex;
  flex-direction: row;
}
.left-content img{
  height: 170px;
  border-radius: 50%;
  margin-left: 200px;
  margin-right: 100px;
}
.right-content{
  display: flex;
  flex-direction: column;

}
.annexe{
  display: flex;
  flex-direction: row;
  margin-top: 25px;
}
.about-me{
  margin-right: 300px;
  margin-bottom: 50px;
}
.contact{
  margin-right: 150px;
}
.contact ul{
  list-style: none;
}
.cvdl{
  
}

</style>
