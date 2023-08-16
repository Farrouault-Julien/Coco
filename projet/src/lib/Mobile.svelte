<script>
  import { link } from "svelte-spa-router";
</script>

<main>
  <div class="menu-page">
    <div class="menu-container">
      <ul>
        <a href="/about" use:link><li class="links">Qui-sommes-nous</li></a>
        <a href="/contact" use:link><li class="links">Contact</li></a>
        <a href="/shop" use:link><li class="links">Chez Coco</li></a>
      </ul>
    </div>
  </div>
</main>

<style>
  main {
    font-family: "Barlow";
    color: rgb(255, 255, 254);
  }

  .menu-page {
    padding: 0;
    margin: 0;
    height: 100vh;
    width: 100%;
    background-color: rgb(236, 153, 136);
  }

  a {
    text-decoration: none;
  }

  li {
    color: rgb(213, 61, 36);
    opacity: 1;
    font-size: 30px;
    margin-top: 15px;
  }

  ul {
    display: flex;
    flex-direction: column;
  }
  .menu-container {
      padding-top: 30%;
      padding-left: 10%;
  }
</style>
