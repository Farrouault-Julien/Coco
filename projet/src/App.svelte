<script>
  import Router from 'svelte-spa-router';
  import About from "./lib/About.svelte";
  import Contact from "./lib/Contact.svelte";
  import Ilot from "./lib/ilot.svelte";
  import Shop from "./lib/Shop.svelte"
  import Mobile from './lib/Mobile.svelte';
  import NotFound from './lib/NotFound.svelte';

  const routes = {
    '/': Ilot,
    '/about': About,
    '/contact': Contact,
    '/shop' : Shop,
    '/menu' : Mobile,
    '*' : NotFound
  }

</script>

<main>

  <Router {routes}/>


</main>


<style>
 

</style>