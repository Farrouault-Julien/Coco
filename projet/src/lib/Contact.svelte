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
          Ou bien sur Dinan dans la boutique chez coco au 14 rue de l’horloge
          22100 Dinan
        </h3>
        <h4>lien vers Maps ci-dessous :</h4>

      </div>
      <div class="contact-bloc">
        <h3>
          Également, vous pouvez passer commande directement en DM sur
          @cocoprendlethe
        </h3>
        <h4>lien vers l'instagram d'Élodie</h4>
        <h4>mail :<mailto /></h4>
        <h4>tel :</h4>
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
    margin-top: 10%;
  }

  .contact-bloc {
    padding-top: 20px;
    width: 40%;
    font-size: 15px;
  }

  img {
    width: 100px;
  }

  h3 {
    margin-bottom: 10px;
    text-align: center;
    
  }

  .info-main-bloc {
    margin-left: 35%;

  }

</style>
