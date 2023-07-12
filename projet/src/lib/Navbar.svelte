
<nav id="navbar">
    <ul>
        <li class="links" id="first_link">Créations</li>
        <li>Qui-sommes-nous</li>
        <li class="links">Contact</li>
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
     font-size: 1.2em;

  }
  #navbar {
    
    display: flex;
    justify-content: flex-end;
    width: 100%;
    line-height: 60px;
    border-bottom:rgb(255, 255, 254) 1px solid;
    
}

/* Mobile Width */ 

@media only screen and (max-width: 600px) {
    li {
      font-size: 20px;
      display: flex;
      justify-content: center;
      padding-left: 0;
    }
    #navbar {
        justify-content: center;
    }
    ul {
        flex-direction: column;
    }
    .links {
        padding-left: 20%;
    }
    #first_link {
        padding-left: 17%;
    }
    }
</style>