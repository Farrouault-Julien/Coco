<script>
  import Navbar from "./Navbar.svelte";
</script>

<main>
  <Navbar />

  <div class="contact-wrapper">
    <div class="contact-main-bloc">
      <img id="logo" alt="logo" src="white-logo.png" />
      <div class="contact-bloc">
        <h3>En vente chez Soleil noir friperie :</h3>
        <h4>3 rue pont aux Foulons à Rennes</h4>
        <a href="#" />
      </div>
      <div class="contact-bloc">
        <h3>
          Ou bien sur Dinan dans la boutique chez coco au 14 rue de l’horloge
          22100 Dinan
        </h3>
        <h4>lien vers Maps ci-dessous :</h4>
        <a href="#" />
      </div>
      <div class="contact-bloc">
        <h3>
          Également, vous pouvez passer commande directement en DM sur
          @cocoprendlethe
        </h3>
        <h4>lien vers l'instagram d'Élodie</h4>
        <a href="#" />
        <h4>mail :<mailto /></h4>
        <h4>tel :</h4>
      </div>
    </div>
  </div>
</main>

<style>
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
    border: 1px solid white;
    border-radius: 25px;
  }

  .contact-bloc {
    width: 40%;
  }

  img {
    width: 400px;
  }
</style>
