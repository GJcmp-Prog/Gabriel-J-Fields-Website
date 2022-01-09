<!DOCTYPE html>
<html lang="en" dir="ltr">
<style>
  body {
    background-image: url("Music BackGround.jpg");
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
    background-color: purple;
    color: white;
  }

  .topnav a.active {
    background-color: black;
    color: purple;
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
    border: 5px solid black;
    height: 300px;
    border-radius: 50%;
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    width: 300px;
  }

  .btn {
    background-color: purple;
    border: none;
    color: silver;
    padding: 12px 16px;
    font-size: 16px;
    cursor: pointer;
  }

  /* Darker background on mouse-over */
  .btn:hover {
    background-color: silver;
    color: purple;
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
    color: purple;
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
    border-color: gold;
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
  <title>Gabriel J Fields Website | Music</title>
</head>

<div class="topnav" id="myTopnav">
  <a href="index.html" class="active">Home</a>
  <a href="#">News</a>
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
      MUSIC
    </center>
  </h1> </br>

  <center>
    <img src="Liberation Single.png" class="circle" alt="Liberation Single Picture">
  </center></br>

  <h2 align="center">Music Projects</h2>
  <table style="width:80%" border="5" align="center">
    <tr bgcolor="black">
      <th>Song Title</th>
      <th>Genre</th>
      <th>Audio</th>
    </tr>
    <tr align="center" bgcolor="black">
      <td>Tidal Wave</td>
      <td>Rap</td>
      <td>
      <object data="Tidal Wave.mp3" width="400px" height="200px"></object>
      </td>
    </tr>
    <tr align="center" bgcolor="black">
      <td>Sorry for Nothin'</td>
      <td>Indie</td>
      <td>
      <object data="Sorry for Nothin'.mp3" width="400px" height="200px"></object>
      </td>
    </tr>
    <tr align="center" bgcolor="black">
      <td>Electronic Sonnet</td>
      <td>Rap</td>
      <td>
      <object data="Electronic Sonnet.mp3" width="400px" height="200px"></object>
      </td>
    </tr>
    <tr align="center" bgcolor="black">
      <td>Freeway</td>
      <td>Indie</td>
      <td>
      <object data="Freeway.mp3" width="400px" height="200px"></object>
      </td>
    </tr>
  </table>

  <hr size="3" noshade></br>
  <button class="btn" onclick="window.location.href='index.html';">
    Home
  </button></br>
<p style="color:white" align="center"><em>Copyright © 2022 | Gabriel J. Fields | All Rights Reserved.</em></p>
</body>

</html>
