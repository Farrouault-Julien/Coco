<div id="home_container">
  <img id="logo" src="white-logo.png" />

  <div id="video_bloc">
    <video autoplay muted loop id="myVideo">
      <source src="./public/bags_video.mov" type="video/mp4" />
    </video>
  </div>
</div>

<style>

  #home_container {
      display: flex;
      float: right;
      width: 100%;
      height: 100vh;
      border: 1px solid black;
      
  }  
  #logo {
    margin-top: 15%;
    height: 200px;
  }

  #myVideo {
      max-width: 400px;
  }
  @media only screen and (max-width: 600px) {
    #logo {
      width: 60%;
      margin-left: 20%;
    }
  }
</style>
