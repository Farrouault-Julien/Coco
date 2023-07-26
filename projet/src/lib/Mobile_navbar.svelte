<script>
import { link } from "svelte-spa-router";
  import Navbar from "./Navbar.svelte";


</script>

<main>
    <Navbar></Navbar>
    <div class="menu-container">
        <ul>
            <a href="/work" use:link><li class="links" id="first_link">Créations</li></a
            >
            <a href="/about" use:link><li class="links">Qui-sommes-nous</li></a>
            <a href="/contact" use:link><li class="links">Contact</li></a>
            <a href="/shop" use:link><li class="links">Chez Coco</li></a>
    
        </ul>
    </div>
</main>

<style>


</style>