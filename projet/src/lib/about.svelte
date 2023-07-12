<script>
</script>

<main>
  <section>
    <div class="left">
      <img id="logo" alt="logo" src="white-logo.png" />
      <h1>Une marque éco-responsable <br /> avec des pièces uniques</h1>
      <h3>
        Les laines et les tissus sont uniques et chinés dans différentes
        ressourcerie ou bien récupérées de vieux vêtements. Bonnets, portes
        gourdes, pochettes, top bag, sac bandoulière, écharpe, et mitaines sont
        fait mains avec des matières premières récupérée. Dans le but de
        respecter notre planète.
      </h3>
    </div>
    <div class="right">
      <img class="rounded-right-img" alt="gants de coco" src="IMG_1122.png" />
    </div>
  </section>

  <section>
    <div class="left">
      <img id="logo" class="scroll" alt="logo" src="chouchou.PNG" />
      <h1>Une marque crée par <br /> Elodie Cornec 23 ans</h1>
      <h3>
        Depuis petite elodie aime créer de ses mains. Manuelle il lui est venue
        naturellement le tricot, le crochet et la couture. Après une école de
        design Produit, elle s’est rendue compte que ces arts autour du fil
        étaient devenue sa passion. Au fur et à mesure elle à su développer
        cette passion en créant cette marque.
      </h3>
    </div>
    <div class="right">
      <img class="rounded-right-img" alt="chouchou" src="IMG_6792.png" />
    </div>
  </section>

  <section>
    <div class="left">
      <img id="logo" class="scroll" alt="logo" src="white-logo.png" />
      <h1>Où nous trouver ?</h1>
      <h3>
        Vous pouvez retrouver nos créations chez Soleil noir friperie 3 rue pont
        aux Foulons sur Rennes Ou bien sur Dinan dans la boutique chez coco au
        14 rue de l’horloge 22100 Dinan Lien de google plan :
        https://goo.gl/maps/kUKt1fMeCEdXaBYC6 Et également prendre des commandes
        sur Instagram en Dm sur @cocoprendlethe Le mail pour la contacter : <mailto
          >elodie.cornec@hotmail.fr</mailto
        > 0672512390
      </h3>
    </div>
    <div class="right">
      <img class="rounded-right-img" alt="gants de coco" src="IMG_6947.jpeg" />
    </div>
  </section>
</main>

<style>
  /* LEFT SIDE */


  section {
    width: 100%;
    height: 100%;
    display: flex;
    scroll-snap-stop: always;
    border-bottom: 1px dashed white;
  }

  .left {

    height: 100vh;
    font-family: "Barlow";
    width: 50%;
    padding-left: 30px;
    color: rgb(255, 255, 254);
  }

  h1 {
    padding-top: 100px;
    font-size: 50px;
    line-height: 50px;
    font-weight: 400;
  }

  h3 {
    line-height: 20px;
    padding-top: 50px;
    width: 50%;
    font-size: 17px;
    font-weight: lighter;
  }

  #logo {
    padding-top: 50px;
    width: 290px;
    height: 158px;
  }

  .scroll {
    visibility: hidden;
  }



  /* RIGHT SIDE */

  .right {
    display: flex;
    width: 50%;
    justify-content: center;
  }
  .rounded-right-img {
    margin-top: 15%;
    width: 500px;
    height: 500px;
    border-radius: 50%;
    border: 1px white solid;
    padding: 20px;
  }

  @media only screen and (max-width: 600px) {
    section {
      flex-direction: column;
    }

    .rounded-right-img {
      border-radius: 50%;
      border: 1px white solid;
      padding: 20px;
      width: 300px;
      height: 300px;
    }

    .left {
      width: 100%;
      padding-right: 30px;
    }

    .right {
      width: 100%;
      padding-right: 30px;
    }
    #logo {
    padding-top: 30px;
    width: 270px;
    height: 158px;
    margin-left: 15%;
   }
   h1 {
     padding-top: 30px;
   }
   h3 {
     position: relative;
     width: 100%;
   }
  }
</style>
