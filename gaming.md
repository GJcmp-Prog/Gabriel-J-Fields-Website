<!DOCTYPE html>
<html lang="en" dir="ltr">
<style>
  body {
    background-image: url("Pacman Maze.png");
  }

  body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
  }

  .topnav {
    overflow: hidden;
    background-color: #333;
  }

  .topnav a {
    float: left;
    display: block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
  }

  .topnav a:hover {
    background-color: red color: white;
  }

  .topnav a.active {
    background-color: black;
    color: red;
  }

  .topnav .icon {
    display: none;
  }

  @media screen and (max-width: 600px) {
    .topnav a:not(:first-child) {
      display: none;
    }

    .topnav a.icon {
      float: right;
      display: block;
    }
  }

  @media screen and (max-width: 600px) {
    .topnav.responsive {
      position: relative;
    }

    .topnav.responsive .icon {
      position: absolute;
      right: 0;
      top: 0;
    }

    .topnav.responsive a {
      float: none;
      display: block;
      text-align: left;
    }
  }

  .circle {
    background-color: black;
    ;
    border: 5px dotted red;
    height: 300px;
    border-radius: 50%;
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    width: 300px;
  }

  .btn {
    background-color: red;
    border: none;
    color: silver;
    padding: 12px 16px;
    font-size: 16px;
    cursor: crosshair;
  }

  /* Darker background on mouse-over */
  .btn:hover {
    background-color: silver;
    color: red;
  }

  p1 {
    color: White;
    font-size: 20px;
    font-family: serif;
  }

  .p2 {
    font-weight: 300;
    color: white;
    font-family: serif;
    font-style: normal;
    font-size: 20px;
  }

  h1 {
    color: red;
    font-family: serif;
  }

  h2 {
    color: White;
    font-family: serif;
  }

  ol {
    color: White;
    font-family: serif;
  }

  th {
    color: White;
    font-family: serif;
  }

  td {
    color: White;
    font-family: serif;
  }

  table {
    border-color: silver;
    border-style: solid;
    border-width: 7px;
  }

  }

  .footer {
    position: relative;
    left: 0;
    bottom: 0;
    width: 100%;
    background-color: none;
    color: white;
    text-align: center;
  }
</style>

<head>
  <meta charset="utf-8">
  <title>Gabriel J Fields Website | Gaming</title>
</head>

<div class="topnav" id="myTopnav">
  <a href="index.html" class="active">Home</a>
  <a href="aboutme.html">About</a>
  <a href="contactme.html">Contact</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>

<div style="padding-left:16px">

</div>

<script>
  function myFunction() {
    var x = document.getElementById("myTopnav");
    if (x.className === "topnav") {
      x.className += " responsive";
    } else {
      x.className = "topnav";
    }
  }
</script>

<body>
  <h1>
    <center>
      GAMING
    </center>
  </h1> </br>

  <center>
    <img src="pacman-video-game.gif" class="circle" alt="Pacman Gif">
  </center>
  <h2 align="center">Favorite Video Games</h2>
  <table style="width:80%" border="2" align="center">
    <tr bgcolor="black">
      <th>Game Title</th>
      <th>Gaming Platform</th>
      <th>Favorite Character(s)</th>
      <th>🎮👾</th>
    </tr>
    <tr bgcolor="black" align="center">
      <td>Madden NFL 22</td>
      <td>PC</td>
      <td>
        <ul>
          <li>
            Dallas Cowboys
          </li>
          <li>
            Houstan Texans
          </li>
          <li>
            Minnesota Vikings
          </li>
        </ul>
      </td>
      <td><img src="Madden Cowboys.gif"/></td>
    </tr>
    <tr bgcolor="black" align="center">
      <td>Street Fighter II</td>
      <td>SNES</td>
      <td>
        <ul>
          <li>
            Ryu
          </li>
          <li>
            Ken
          </li>
          <li>
            Blanka
          </li>
        </ul>
      </td>
      <td><img src="Ryu.gif"/></td>
    </tr>
    <tr bgcolor="black" align="center">
      <td>Mortal Kombat 11</td>
      <td>PC</td>
      <td>
        <ul>
          <li>
            Noob Saibot
          </li>
          <li>
            Scorpion
          </li>
          <li>
            Kung Lao
          </li>
        </ul>
      </td>
      <td><img src="Noob.gif"/></td>
    </tr>
    <tr bgcolor="black" align="center">
      <td>Sonic The Hedgehog</td>
      <td>Sega Genesis</td>
      <td>
        <ul>
          <li>
            Sonic
          </li>
          <li>
            Shadow
          </li>
          <li>
            Knuckles
          </li>
        </ul>
      </td>
      <td><img src="Sonic.gif"/></td>
    </tr>
  </table>
  <h2 align="center">Favorite Gaming Consoles</h2>
  <table align="center">
    <ol type="I">
    <tr bgcolor="black">
      <td>
        <li><a href="https://atari.fandom.com/wiki/Atari_Wiki">Atari</li></a>
      </td>
    </tr>
    <tr bgcolor="black">
      <td>
          <li><a href="https://nintendo.fandom.com/wiki/Nintendo_Entertainment_System">NES</li></a>
      </td>
    </tr>
    <tr bgcolor="black">
      <td>
          <li><a href="https://sega.fandom.com/wiki/Mega_Drive">Sega Genesis</li></a>
      </td>
    </tr>
    <tr bgcolor="black">
      <td>
        <li><a href="https://nintendo.fandom.com/wiki/Super_Nintendo_Entertainment_System">SNES</a></li>
      </td>
    </tr>
    </ol>
  </table>



  <hr size="3" noshade></br>
  <button class="btn" onclick="window.location.href='index.html';">
    Home
  </button></br>
    <p style="color:white" align="center"><em>Copyright © 2022 | Gabriel J. Fields | All Rights Reserved.</em></p>
</body>

</html>
