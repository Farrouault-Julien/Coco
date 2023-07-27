<script>
  import Navbar from "./Navbar.svelte";
</script>

<main>
  <div class="shop_wrapper">
    <Navbar />

    <div class="header">
      <div class="header-logo">
        <h1>CHEZ COCO</h1>
      </div>
      <div class="summary">
        <h3>
          Une boutique familliale mettant en avant l'art du cuir, du fusing et
          les petits créateurs
        </h3>
      </div>
      <div class="border" />
      <div class="arrow">
        <i
          class="fa-regular fa-arrow-down fa-bounce fa-3x"
          style="color: #ffffff;"
        />
      </div>
    </div>
    <div class="main">
      <div class="left">
        <img class="main-photo" src="IMG_6228.jpeg" alt="Giuseppe" />
      </div>

      <div class="right">
        <p>
          Chez coco est une boutique familiale, auparavant tenue par Giuseppe
          Coppola et sous le nom de « Galerie d’Art » depuis 35 ans dans tous
          les coins de la France. Celle ci met en avant l’art du cuir, les
          créations artisanales, et le fusing. Implantée sur Dinan depuis 14
          ans, elle à su se developper en proposition.
        </p>
        
        <p>
          Aujourd’hui cette boutique à été reprise par Chloé et Elodie Cornec -
          Coppola, ses filles. Elles ont agrandit la boutique, en créant
          différents espaces distinct tout en gardant le savoir faire de
          l’enseigne. Le premier partie expose l’art du cuir et du verre, et la
          seconde propose un lieu d’exposition de jeunes créateurs dont une
          friperie, et une brocante.
        </p>
      </div>
    </div>

    <div class="main">
      <div class="left">
        <img class="main-photo" src="IMG_5800.jpeg" alt="devanture" />
      </div>
            <div class="right">
        <p>
          Chez coco est maintenant repris par Chloé 19 ans et Elodie 23 ans,
          deux artistes couturières aimant les loisirs créatifs. Elle est
          devenue une boutique de petits créateurs tout en gardant l’art du cuir
          fait sur mesure et du verre transmis par leurs père. Baignant dans
          l’art, elles ont ajouté leurs créations au lieu, vous y trouverez des
          sacs fait main, des mitaines tricotés, des bonnets en crochets ainsi
          que des portes gourdes etc...
        </p>
        <p>
          Vous y retrouverez également des créations de Clement Coppola autour
          du verre. De la photographie fait par Gregoire Garnier. Ainsi que des
          illustrations d’Adele Vuillemot une graphiste. Et pleins d’autres à
          venir...
        </p>
      </div>
    </div>

    <div class="main">
      <div class="left">
        <img class="main-photo" src="IMG_5787.jpeg" alt="interieur-boutique" />
      </div>

      <div class="right">
        <p class="title">Où nous-trouver ?</p>
        <p>
          14 rue de l’horloge 22100 Dinan<br /> En face de la tour de l’horloge Possibilité
          de se garer place Duguesclin sauf le jeudi jour de marché.
        </p>
        <p class="title">Horaires :</p>
        <p>
          Lundi 11h -18h30 <br /> Mardi 11h - 18h30 <br />Mercredi 11h - 18h30<br
          />
          Jeudi : Fermé
          <br />Vendredi 11h - 18h 30 <br />Samedi 11h - 18h 30 <br />Dimanche :
          Fermé
        </p>
        <p class="title">Lien Maps ci-dessous :</p>
        <a class="arrow" href="https://goo.gl/maps/kUKt1fMeCEdXaBYC6"
          ><i
            class="fa-solid fa-map-location-dot fa-beat-fade fa-4x"
            style="color: #ffffff;"
          /></a
        >
      </div>
    </div>
  </div>
</main>

<style>
  @media screen and (min-width: 320px) and (max-width: 767px) and (orientation: landscape) {
  main {
    transform: rotate(-90deg);
    transform-origin: left top;
    width: 100vh;
    overflow-x: hidden;
    position: absolute;
    top: 100%;
    left: 0;
  }

}
  main {
    font-family: "Barlow";
    color: rgb(255, 255, 254);
    overflow-x: hidden;
  }
  .shop_wrapper {
    padding: 0;
    margin: 0;
    height: 430vh;
    background-color: rgb(25, 40, 31);
    background-size: 100% 100%;
    background-size: cover;
    background-attachment: fixed;
  }

  /* HEADER PART */

  .header {
    height: 100vh;
    display: flex;
    flex-direction: column;
    gap: 5%;
    align-items: center;
  }

  .header-logo {
    font-size: 80px;
    margin-top: 30%;
    text-align: center;
  }

  .summary {
    padding-top: 20%;
    width: 80%;
  }

  h3 {
    font-size: 20px;
    text-align: center;
  }

  .border {
    width: 30%;
    border: 1px solid white;
  }

  /* MAIN PART */
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

  .arrow {
    display: flex;
    justify-content: center;
  }



</style>
