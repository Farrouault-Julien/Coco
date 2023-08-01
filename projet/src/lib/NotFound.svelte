<script>
  import { link } from "svelte-spa-router";
</script>

<main />

<div class="main-wrapper">
  <div class="error-message">
    <h1>ERROR 404</h1>
    <h2>The page you are looking for cannot be found</h2>
    <a href="/" use:link><div class="home">Accueil</div></a>
  </div>
</div>

<style>
  .main-wrapper {
    font-family: "Barlow";
    color: rgb(255, 255, 254);
    height: 100vh;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .error-message {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
  }

  h1 {
      font-size: 100px;
      font-weight: bold;
      margin-bottom: 10%;
  }
  h2 {
      font-size: 20px;
      margin-bottom: 10%;
  }
  a {
      text-decoration: none;
      color: rgb(255, 255, 254);
      font-size: 20px;
  }

  a:hover {
      background-color: rgb(255, 255, 254);
      color: rgb(213, 61, 36);
      border-radius: 25px;
  }

  .home {
      border-radius: 25px;
      border: 1px solid rgb(255, 255, 254);
      padding: 15px;
  }
</style>
