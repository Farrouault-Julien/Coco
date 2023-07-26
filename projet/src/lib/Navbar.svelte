<script>
  import { link } from "svelte-spa-router";
</script>

<nav id="navbar">
  <div class="logo">
    <a href="/" use:link><img src="white-logo.png" alt="home" /></a>
  </div>
  <ul>
    <a href="/work" use:link><li class="links" id="first_link">Créations</li></a
    >
    <a href="/about" use:link><li class="links">Qui-sommes-nous</li></a>
    <a href="/contact" use:link><li class="links">Contact</li></a>
    <a href="/shop" use:link><li class="links">Chez Coco</li></a>
    <a href="/menu" use:link
      ><li class="mobile">
        <i class="fa-sharp fa-solid fa-bars fa-2xl" style="color: #ffffff;" />
      </li></a
    >
  </ul>
</nav>

<style>
  ul {
    display: flex;
    margin-right: 20px;
  }

  li {
    color: rgb(255, 255, 254);
    display: inline;
    padding: 10px;
    font-size: 15px;
  }
  a {
    text-decoration: none;
    padding: 10px;
  }
  #navbar {
    display: flex;
    justify-content: space-between;
    width: 100%;
    line-height: 60px;
  }

  img {
    width: 130px;
    height: 70px;
  }

  .logo {
    padding-top: 15px;
    padding-left: 20px;
    position: relative;
  }

  .mobile {
    display: none;
  }

  /* Mobile Width */

  @media only screen and (max-width: 600px) {

    .links {
      visibility: hidden;
    }

    .mobile {
      display: block;
      position: absolute;
      right: 30px;
    }

  }
</style>
