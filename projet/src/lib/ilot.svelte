<div id="home_container">

  <img id="logo" src="white-logo.png" />

  <img id="img1" src="output.PNG" />
  <img id="img2" src="photo-output 8.PNG" />
  <img id="img3" src="photo-output 9.PNG" />


</div>

<style>

  #home_container {
      display: flex;
      justify-content: space-around;
      width: 100%;
      height: 90vh;
      
  } 
  
 
  #logo {
    margin-top: 15%;
    height: 200px;
    position: absolute;
    left: 50px;
  }

  @media only screen and (max-width: 600px) {
    #logo {
      width: 80%;
      
    }

    #img1 {
      visibility: hidden;
    }
    #img2 {
      visibility: hidden;
    }
    #img3 {
      visibility: hidden;
    }

  }
</style>
