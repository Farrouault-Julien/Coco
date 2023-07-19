<script>
  import { fade, slide, blur } from "Svelte/transition";
  import Navbar from "./Navbar.svelte";
  import { link } from "svelte-spa-router";
</script>

<main>
  <div class="home">
    <div id="home_container">
      <img transition:blur= {{duration: 1000}} id="logo" src="white-logo.png" />
      <ul>
        <a href="/work" use:link><li class="links" id="first_link">Créations</li></a
        >
        <a href="/about" use:link><li class="links">Qui-sommes-nous</li></a>
        <a href="/contact" use:link><li class="links">Contact</li></a>
        <a href="/shop" use:link><li class="links">Chez Coco</li></a>

      </ul>

    </div>
  </div>
</main>

<style>

  ul {
    display: flex;
    flex-direction: column;
    margin-top: 20px;
    margin-left: 20px;
  }

  li {
    color: #f0f0f0;
    font-size: 20px;
    line-height: 40px;
  }

  a {
    text-decoration: none;
  }

  a:hover {
    cursor: pointer;
  }
  .home {
    padding: 0;
    margin: 0;
    height: 100vh;
    background: url("IMG_1122.png");
    background-size: 100% 100%;
    background-size: cover;
    background-attachment: fixed;
  }
  #home_container {
    display: flex;
    flex-direction: column;
    width: 100%;
    height: 90vh;
  }

  #logo {
    margin-top: 20%;
    width: 350px;
    height: 200px;
    left: 20px;
  }

  @media only screen and (max-width: 600px) {
    #logo {
      width: 80%;
    }

  }
</style>
