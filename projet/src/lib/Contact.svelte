<script>
  import Navbar from "./Navbar.svelte";
</script>

<main>
  <Navbar />

  <div class="contact-wrapper">
    <div class="contact-main-bloc">
      <img id="logo" alt="logo" src="white-logo.png" />
      <div class="info-main-bloc">
        <div class="contact-bloc">
        <h3>En vente chez Soleil noir friperie :</h3>
        <h4>3 rue pont aux Foulons à Rennes</h4>

      </div>
      <div class="contact-bloc">
        <h3>
          Ou bien sur Dinan dans la boutique chez coco
        </h3>
        <h4 id="before-icon">lien vers Maps ci-dessous :</h4>
        <a class="arrow" href="https://goo.gl/maps/kUKt1fMeCEdXaBYC6"
        ><i
          class="fa-solid fa-map-location-dot fa-beat-fade fa-4x"
          style="color: #ffffff;"
        /></a>
      </div>
      <div class="contact-bloc">
        <h3>
          Également, vous pouvez passer commande directement en DM sur
          <a href="https://www.instagram.com/cocoprendlethe/"><p>@cocoprendlethe</p></a>
        </h3>
        <h4>mail : <a href="mailto:elodie.cornec@hotmail.fr">elodie.cornec@hotmail.fr</a>
        <h4>tel : 0672512390</h4>
      </div>
      </div>
      
    </div>
  </div>
</main>

<style>

@media only screen and (max-width: 600px) {
  .contact-main-bloc {
    flex-direction: column;
  }
}
  main {
    font-family: "Barlow";
    color: rgb(255, 255, 254);
  }

  .contact-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    height: 100vh;
  }

  .contact-main-bloc {
    display: flex;
    align-items: center;
    margin-top: 5%;
  }

  .contact-bloc {
    padding-top: 20px;
    padding-bottom: 20px;
    width: 40%;
    font-size: 15px;
  }

  img {
    width: 200px;
  }

  h3 {
    margin-bottom: 10px;
    text-align: center;
    
  }

  .info-main-bloc {
    margin-left: 25%;
    border-radius: 25px;
    border: 1px solid rgb(255, 255, 254);
    padding-top: 30px;
    padding-bottom: 30px;
    padding-left: 40px;
    padding-right: 40px;

  }
  a {
      text-decoration: none;
      color: rgb(255, 255, 254);
    }

  .arrow {
    padding-top: 10px;
  }

  #before-icon {
    margin-bottom: 20px;
  }
  @media (min-width: 743px) {
    .contact-bloc {
      width: 100%;
    }
    h3 {
      text-align: start; 
      font-size: 20px;
      font-weight: bold;
    }
    h4 {
      font-size: 20px;
    }
    .arrow {
      margin-left: 30%;
    }

    
  }

</style>
