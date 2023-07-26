<script>
  import Navbar from "./Navbar.svelte";

</script>

<main>
  <div class="shop_wrapper">
    <Navbar />
    <div class="header">
      <div class="header-logo">
        <img
          id="summary-logo"
          src="white-logo.png"
          alt="logo"
        />
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
            <i class="fa-regular fa-hand fa-bounce fa-4x" style="color: #ffffff;"></i>
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

      <div class="left">
        <img class="main-photo" src="IMG_5800.jpeg" alt="devanture" />
      </div>
    </div>

    <div class="main">
      <div class="left">
        <img class="main-photo" src="elodie.jpg" alt="elodie" />
      </div>

      <div class="right">
        <p>
          14 rue de l’horloge 22100 Dinan En face de la tour de l’horloge
          Possibilité de se garer place Duguesclin sauf le jeudi jour de marché.
        </p>
        <p>
          Lundi 11h -18h30 <br /> Mardi 11h - 18h30 <br />Mercredi 11h - 18h30<br
          />
          Jeudi Fermé
          <br />Vendredi 11h - 18h 30 <br />Samedi 11h - 18h 30 <br />Dimanche
          Fermé
        </p>
        <p>
          14 rue de l’horloge 22100 Dinan<br /> En face de la tour de l’horloge<br
          />
          Possibilité de se garer place Duguesclin sauf le jeudi jour de marché.
        </p>
      </div>
    </div>
  </div>
</main>

<style>

@media only screen and (max-width: 600px) {

  #summary-logo {
    width: 40%;

  }

  .main {
    flex-direction: column;
  }

  .main-photo {
    width: 200px;
  }


}

  
  main {
    font-family: "Barlow";
    color: rgb(255, 255, 254);
  }
  .shop_wrapper {
    padding: 0;
    margin: 0;
    height: 500vh;
    background-color: rgb(213, 61, 36);
    background-size: cover;
    background-attachment: fixed;
  }

  .header {
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 100%;
    height: 100vh;
  }
  .header-logo {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  #summary-logo {
    border: none;
    margin-bottom: 20px;
  }

  .summary {
    display: flex;
    height: 200px;
    width: 100%;
    justify-content: space-around;
    align-items: center;
  }
  .fa-icon {
    padding-left: 45%;
  }

  .icon {
    width: 30%;
  }

  h3 {
    font-size: 20px;
    padding-top: 30px;
    text-align: center;
  }

  .border {
    width: 200px;
    border: 1px solid white;
    margin-left: 44%;
    margin-top: 40px;
  }

  /* SECOND SLIDE */

  .main {
    width: 100%;
    height: 120vh;
    display: flex;
  }
  .left {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    width: 50%;
  }

  .right {
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .main-photo {
    width: 479px;
    height: 619px;
  }

  img {
    border-radius: 25px;
    border: 1px solid white;
    padding: 20px;
    object-fit: cover;
  }

  p {
    width: 50%;
    font-size: 25px;
    justify-content: center;
    align-items: center;
    border-left: 1px solid white;
    padding-left: 20px;
    line-height: 1.2em;
    margin-top: 20px;
  }
</style>
