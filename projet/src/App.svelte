<script>
  import Router from 'svelte-spa-router';
  import About from "./lib/About.svelte";
  import Contact from "./lib/Contact.svelte";
  import Ilot from "./lib/ilot.svelte";
  import Navbar from "./lib/Navbar.svelte";
  import Work from "./lib/Work.svelte";
  import Shop from "./lib/Shop.svelte"
  import Mobile_navbar from './lib/Mobile_navbar.svelte';

  const routes = {
    '/': Ilot,
    '/about': About,
    '/work': Work,
    '/contact': Contact,
    '/shop' : Shop,
    '/menu' : Mobile_navbar
  }

</script>

<main>

  <Router {routes}/>


</main>


<style>
 

</style>