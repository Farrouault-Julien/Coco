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
    </div>
    <div class="main">
      <div class="left">
        <img class="main-photo" src="IMG_6228.jpeg" alt="devanture" />
      </div>

      <div class="right">
        <p>
          Chez coco est une boutique familiale, auparavant tenue par Giuseppe
          Coppola et sous le nom de « Galerie d’Art » depuis 35 ans dans tous
          les coins de la France. Celle ci met en avant l’art du cuir, les
          créations artisanales, et le fusing. Implantée sur Dinan depuis 14
          ans, elle à su se developper en proposition. Aujourd’hui cette
          boutique à été reprise par Chloé et Elodie Cornec - Coppola, ses
          filles. Elles ont agrandit la boutique, en créant différents espaces
          distinct tout en gardant le savoir faire de l’enseigne. Le premier
          partie expose l’art du cuir et du verre, et la seconde propose un lieu
          d’exposition de jeunes créateurs dont une friperie, et une brocante.
        </p>
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
    height: 1000vh;
    background: url("mesh-gradient-7.png");
    background-size: 100% 100%;
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
    padding-top: 100px;
  }

  .summary {
    display: flex;
    height: 200px;
    width: 100%;
    justify-content: center;
    align-items: center;
  }
  h1 {
    font-size: 200px;
  }

  h3 {
    font-size: 20px;
    width: 30%;
    text-align: center;
  }

  .border {
    width: 200px;
    border: 1px solid white;
    margin-left: 43%;
  }

  /* SECOND SLIDE */

  .main {
    width: 100%;
    height: 100vh;
    display: flex;
  }
  .left {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 50%;
  }

  .right {
    width: 50%;
    display: flex;
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
    font-size: 20px;
    justify-content: center;
    align-items: center;
    border-left: 1px solid white;
    padding-left: 20px;
    line-height: 1.2em;
  }
</style>
