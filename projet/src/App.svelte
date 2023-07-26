<script>
  import Router from 'svelte-spa-router';
  import About from "./lib/About.svelte";
  import Contact from "./lib/Contact.svelte";
  import Ilot from "./lib/ilot.svelte";
  import Work from "./lib/Work.svelte";
  import Shop from "./lib/Shop.svelte"
  import Mobile from './lib/Mobile.svelte';

  const routes = {
    '/': Ilot,
    '/about': About,
    '/work': Work,
    '/contact': Contact,
    '/shop' : Shop,
    '/menu' : Mobile,
  }

</script>

<main>

  <Router {routes}/>


</main>


<style>
 

</style>