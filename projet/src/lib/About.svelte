<script>
  import Navbar from "./Navbar.svelte";
</script>

<main>
  <div class="shop_wrapper">
    <Navbar />
    <div class="header">
      <div class="header-intro">
        <h1>Qui-Sommes-nous ?</h1>
      </div>
      <div class="summary">
        <div class="icon">
          <div class="fa-icon">
            <i
              class="fa-solid fa-recycle fa-spin fa-4x"
              style="color: #f0000;"
            />
          </div>
          <div class="under-icon-texte">
            <h3>Des matériaux chinés<br /> et/ou recylés</h3>
          </div>
        </div>
        <div class="icon">
          <div class="fa-icon">
            <i
              class="fa-solid fa-puzzle-piece fa-beat-fade fa-4x"
              style="color: #ffffff;"
            />
          </div>
          <div class="under-icon-texte">
            <h3>Des pièces uniques</h3>
          </div>
        </div>
        <div class="icon">
          <div class="fa-icon">
            <i
              class="fa-regular fa-hand fa-bounce fa-4x"
              style="color: #ffffff;"
            />
          </div>
          <div class="under-icon-texte">
            <h3>Handmade</h3>
          </div>
        </div>
      </div>
      <div class="border" />
    </div>
    
    <div class="main">
      <div class="left">
        <img class="main-photo" src="IMG_1122.png" alt="Giuseppe" />
      </div>

      <div class="right">
        <p>
          Coco prend le thé est une marque crée par Elodie Cornec 23 ans. Depuis
          petite elodie aime créer de ses mains. Manuelle il lui est venue
          naturellement le tricot, le crochet et la couture. Après une école de
          design Produit, elle s’est rendue compte que ces arts autour du fil
          étaient devenue sa passion. Au fur et à mesure elle à su développer
          cette passion en créant cette marque.
        </p>
        <div class="border"></div>
      </div>
    </div>

    <div class="main">
      <div class="left">
        <img class="main-photo" src="IMG_5800.jpeg" alt="devanture" />
      </div>
      <div class="right">
        <p>
          Cette marque eco-responssable, crée des pièces uniques. Les laines et
          les tissus sont uniques et chinés dans différentes ressourcerie ou
          bien récupérées de vieux vêtements. Bonnets, portes gourdes,
          pochettes, top bag, sac bandoulière, écharpe, et mitaines sont fait
          mains avec des matières premières récupérée. Dans le but de respecter
          notre planète.
        </p>
        <div class="border"></div>
      </div>
    </div>

    <div class="main">
      <div class="left">
        <img class="main-photo" src="elodie.jpg" alt="elodie" />
      </div>

      <div class="right">
        <p>
          Vous pouvez retrouver ses créations chez Soleil noir friperie 3 rue
          pont aux Foulons sur Rennes
        </p>
        <p>
          Ou bien sur Dinan dans la boutique chez coco au 14 rue de l’horloge
          22100 Dinan Lien de google plan :
          https://goo.gl/maps/kUKt1fMeCEdXaBYC6
        </p>
        <p>
          Et également prendre des commandes sur Instagram en Dm sur
          @cocoprendlethe Le mail pour la contacter : elodie.cornec@hotmail.fr
          0672512390
        </p>
        <div class="border"></div>
      </div>
    </div>
  </div>
</main>

<style>
  main {
    font-family: "Barlow";
    color: rgb(255, 255, 254);
  }
  .shop_wrapper {
    padding: 0;
    margin: 0;
    height: 400vh;
    background-color: rgb(213, 61, 36);
    background-size: cover;
    background-attachment: fixed;
  }

  .header {
    display: flex;
    flex-direction: column;
    width: 100%;
    height: 100vh;
    margin-top: 10%;
  }

  .header-intro {
    text-align: center;
    font-size: 45px;
    margin-bottom: 40%;
  }


  .summary {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    height: 200px;
    width: 100%;

    align-items: center;
  }
  .fa-icon {
    padding-left: 30%;
    padding-top: 20%;
  }

  .icon {
    width: 30%;
  }

  h3 {
    font-size: 15px;
    padding-top: 30px;
    text-align: center;
  }

  .main {
    display: flex;
    flex-wrap: wrap;
    height: 100vh;
  }
  .main-photo {
    height: fit-content;
    width: 100%;
    height: 100%;
  }

  img {
    width: 100%;
    object-fit: cover;
  }

  .left {
    width: 100%;
    height: 300px;
    display: flex;
    justify-content: center;
  }

  .right {
    width: 100%;
    height: 300px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  p {
    font-size: 20px;
    padding-bottom: 20px;
    padding-left: 20px;
    padding-right: 20px;
    text-align: center;
  }
  .border {
    border: 1px solid white;
    width: 10%;
    margin-left: 45%;
  }
</style>
