<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lil Peep</title>
  <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/3529/3529273.png">

  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: black;
      color: white;
      padding: 0.5%;
    }

    section {
      height: 100vh;
    }

    .onesec {
      position: relative;
      background-image: url('https://www.rollingstone.com/wp-content/uploads/2019/03/Lil-Peep-by-Alex-Reside-49L.jpg?w=1600&h=900&crop=1');
      background-size: cover;
      background-position: center;
      color: white;
    }

    .onesec::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background-color: rgba(0, 0, 0, 0.5);
      z-index: 1;
    }

    .nav {
      padding: 2%;
      text-align: end;
      z-index: 2;
      position: relative;
    }

    .click {
      text-decoration: none;
      color: white;
      margin: 2%;
      transition:0.3s;
    }

    .click:hover{
      color:red;
    }

    .intro {
      font-size: 190%;
      padding: 2%;
      margin-right: 20%;
      margin-top: 2%;
      z-index: 2;
      position: relative;
      transform: scale(0.5);
      opacity: 0;
      animation: popup 0.9s ease-out forwards;
      animation-delay: 0.5s;
    }

    @keyframes popup {
      to {
        opacity: 1;
        transform: scale(1);
      }
    }

    .discover {
      background-color: rgb(56, 54, 54);
      padding: 2%;
      font-size: 50%;
      border: none;
      cursor: pointer;
      opacity: 0.5;
      width: 30%;
      border-radius: 2%;
      transition: 0.5s;
      color:white;
      border: solid;
    }

    .discover:hover {
      border: solid;
      background-color: black;
      opacity: 1;
      border-radius: 2%;
    }

    #twosec {
      background-color: rgb(15, 15, 15);
      padding: 20px;
    }

    .division {
      display: flex;
      justify-content: center;
      gap: 3%;
      flex-wrap: wrap;
      padding: 0.5%;
      width: 90%;
      margin-bottom: 5%;
    }

    .first {
      background-color: rgba(88, 78, 78, 0.493);
      color: black;
      padding: 1%;
      width: 100%;
      max-width: 300px;
      border-radius: 5%;
      transition: 0.5s;
      opacity: 0.5;
      margin-top: 2%;
      margin-bottom: 2%;
    }

    .first:hover {
      transform: scale(1.1);
      opacity: 1;
      color: white;
    }

    .disc {
      background-color: black;
      color: white;
      font-size: 90%;
      padding: 5%;
      text-decoration: none;
      border-radius: 10%; 
      opacity: 0.5;
      transition: 0.5s;
    }

    .disc:hover {
      opacity: 1;
      border-radius: 0;
    }

    @media screen and (max-width: 768px) {
      .intro {
        font-size: 120%;
        margin-right: 10%;
      }

      .division {
        flex-direction: column;
        align-items: center;
      }

      .first {
        width: 80%;
      }

      .discover {
        width: 50%;
        font-size: 75%;
      }
    }

    @media screen and (max-width: 480px) {
      .intro {
        font-size: 100%;
      }

      .discover {
        width: 60%;
        font-size: 60%;
      }
    }


    .down{
      background-color: rgb(39, 38, 38);
      padding:2%;
      text-decoration: none;
      color:white;
      border-radius: 40%;
      
      
    }

    .lilpeep{
      background-image: url('https://4kwallpapers.com/images/wallpapers/lil-peep-american-3840x2160-13767.jpg');
      background-size: cover;                 
      background-position: center;            
      background-repeat: no-repeat;           
      height: 100vh;
      
      
        
    }

    .hi{
      justify-content: center;
      display: flex;
      align-items: center;
      height: 100vh;
      
    }

    .hide{
      text-decoration: none;
      color:white;
      transition: 0.5s;
    }

    .hide:hover{
      color: red;
    }

    .hidemusic{
      text-decoration: none;
      color:white;
      transition: 0.5s;
    }

    .hidemusic:hover{
      color:red;

      
    }

    .forth{
      display: flex;
      align-items: center;
      justify-content: center;
      padding:2%;
      background-color: rgb(12, 12, 12);
    }

  

    .album{
      padding:20%;
    }


    .try{
      background-color: rgb(43, 42, 42);
      padding:2%;
      border-radius: 5%;
    }


    .come{
      background-color: black;
      padding:1%;
      margin:1%;
      align-items: center;
      display: flex;
      border-radius: 0.5%;
      transition:0.5s;
      opacity: 0.5;
      
    }

    .come:hover{
      transform: scale(1.2);
      opacity: 1;
      background-color: rgb(15, 15, 15);
      border: 1px solid white
    }

    .come p{
      font-size: 80%;
      margin: 2%;

    }

    .hellboy{
      background-color: black;
      padding:1%;
      margin:1%;
      align-items: center;
      display: flex;
      border-radius: 0.5%;
      transition:0.5s;
      opacity: 0.5;
      
    }

    .hellboy:hover{
      transform: scale(1.2);
      opacity: 1;
      background-color: rgb(15, 15, 15);
      border: 1px solid white
    }

    .hellboy p{
      font-size: 80%;
      margin: 2%;

    }

    .crybaby{
      background-color: black;
      padding:1%;
      margin:1%;
      align-items: center;
      display: flex;
      border-radius: 0.5%;
      transition:0.5s;
      opacity: 0.5;
    }

    .crybaby:hover{
      transform: scale(1.2);
      opacity: 1;
      background-color: rgb(15, 15, 15);
      border: 1px solid white
    }

    .crybaby p{
      font-size: 80%;
      margin: 2%;

    }

    .lilup{
      font-size:120%;
      transition: 0.5s;
      cursor: pointer;
      text-decoration: none;
      color:white;

    }

    .lilup:hover{
      color:red;
    }

    .play{
      background-color: rgb(31, 30, 30);
      width:10%; 
      text-align: center;
      padding:1%;
      text-decoration: none ;
      color:white;
      border-radius: 5%;
      transition: 0.5s;
    }

    .play:hover{
      background-color:rgb(65, 63, 63);
      color:white
    }

    



 


  </style>
</head>
<body>

  <section class="onesec" id="onesec">
    <div class="nav">
      <nav>
        <a class="click" href="#onesec">HOME</a>
        <a class="click" href="#threesec">ABOUT</a>
        <a class="click" href="#fourthsec">MUSICS</a>
      </nav>
    </div>

    <div class="intro">
      <h1>Welcome! This site, designed by Yyo Angelo Escobido, reflects his knowledge and skills in web design.</h1>
      <a href="#twosec"><button class="discover">DISCOVER</button></a>
    </div>
  </section>

  <section id="twosec">
    <center>
      <h1>DISCOVER</h1>

      <div class="division">
        <div class="first">
          <h2>Lil Peep</h2>
          <img style="width: 80%; height: 65%; margin-bottom: 7%;" src="https://c4.wallpaperflare.com/wallpaper/765/940/903/lil-peep-music-hd-wallpaper-preview.jpg">
          <br><a class="disc" href="#threesec">Discover</a>
        </div>

        <div class="first">
          <h2>Albums</h2>
          <img style="width: 80%; height: 65%; margin-bottom: 7%;" src="https://preview.redd.it/xno7xy00c7021.png?auto=webp&s=9ee50ccce802e0e049ef78cfa71044104c7cf948">
          <br><a class="disc" href="#fourthsec">Discover</a>
        </div>

        <div class="first">
          <h2>Spotify</h2>
          <img style="width: 80%; height: 65%; margin-bottom: 7%;" src="https://thisis-images.spotifycdn.com/37i9dQZF1DZ06evO1kxsTC-default.jpg">
            <br><a class="disc" href="#fourthsec">Discover</a>
        </div>
      </div>
      </center>
    <center>
      
        <a class = "down" href = "#threesec"> ↓ </a>
        <a class = "down" href = "#onesec"> ↑ </a>
    </center>
      
  </section>

<section class = "lilpeep" id = "threesec">

<div class = "hi">
  <a class = "hide" href = "#twosec"> <h1 style = "font-size:500%;"> Hi im Lil Peep </h1> </a>
  
  <a class = "hidemusic" href = "#fourthsec"><p> MUSIC </p></a> 
  
</div>

</section>

<section class = "forth" id = "fourthsec">



<div class = "album">
  <center>
      <h1> ALBUM </h1>
  </center>

<div class = "try">
  

  <div class = "come">
    <img style = "width:15%;" src = "https://m.media-amazon.com/images/I/71lvjdR4k9L._UF1000,1000_QL80_.jpg">
    <p> <font style = "font-size: 200%;">Come Over When You're Sober, Pt. 1 (2017)</font> <br><br>
      BEST SONGS: "Save That Shit," "U Said," "Better Off (Dying)," and "The Brightside"
      <br>
      <br>
      WORST SONG: "Awful Things"
      <br>
      <br>
      10/10
    </p>
    
    <a class = "play" href = "https://www.youtube.com/watch?v=XyKkeymBceM&list=PLwjGGj4MHr7_x-4Mrq_uF6o9NktktCUEU" target="_blank"> ▶ </a>
  </div>


  <div class = "hellboy">
    <img style = "width:15%;;" src = "https://www.turntablelab.com/cdn/shop/files/lilpeep-hellboy-coloredvinyl-1_1000x1000.jpg?v=1696605517">
    <p>
      <font style = "font-size: 200%;"> Hellboy (2016) [Mixtape] </font> <br>
      <br>
      BEST SONGS: "world away," "cobain," "gucci mane," "we think too much," and "walk away as the doors slams"
      <br>
      <br>
      WORST SONG: "move on, be strong"
      <br>
      <br>
      10/10</p>
      <a class = "play" href = "https://www.youtube.com/watch?v=hmAFZZ9D2fc&list=PLT_N8wVy0sP-9fGiG4MAeCVft4EBcRBIE" target="_blank"> ▶ </a>
  </div>

  <div class = "crybaby">
    <img style = "width:15%;" src = "https://lilpeep.com/cdn/shop/files/crybabycdlilpeep2.png?v=1686403965">
    <p> <font style = "font-size: 200%;"> Crybaby (2016) [Mixtape] </font> <br>
      <br>
BEST SONGS: "crybaby," "lil jeep," "white tee," and "driveway"
      <br>
      <br>
WORST SONG: "nineteen" (yes I know, don't roast me.)
      <br>
      <br>
10/10
    </p>
    <a class = "play" href = "https://www.youtube.com/results?search_query=come+over+when+you%27re+sober+part+1+lil+peep" target="_blank"> ▶ </a>
  </div>
</div>
<center>
  <a class = "lilup" href = "#threesec"><p> Lil Peep </p></a>
</center>
</div>


</section>


</body>
</html>
