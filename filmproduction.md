<!DOCTYPE html>
<html lang="en" dir="ltr">
<style>
  body {
    background-image: url("BackGround.jpg");
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
    background-color: green;
    color: white;
  }

  .topnav a.active {
    background-color: black;
    color: green;
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

  table {
    border-color: silver;
    border-style: solid;
    border-width: 7px;
  }

  .btn {
    background-color: green;
    border: none;
    color: silver;
    padding: 12px 16px;
    font-size: 16px;
    cursor: pointer;
  }

  /* Darker background on mouse-over */
  .btn:hover {
    background-color: silver;
    color: green;
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
    color: green;
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
    border-color: Silver;
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
  <title>Gabriel J Fields Website | Film Production</title>
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
      FILM PRODUCTION
    </center>
  </h1> </br>

  <center>
    <img src="Cartoon Me.png" class="circle" alt="Picture of cartoon Gabriel">
  </center></br>

  <h2 align="center">Production Projects</h2>
  <table style="width:80%" border="2" align="center">
    <tr>
      <th>Film Title</th>
      <th>Description</th>
      <th>Video</th>
    </tr>
    <tr align="center">
      <td><strong>Thirty (2021)</strong></td>
      <td>A short self-shot documentary about what I have learned about life from living my 20s.</td>
      <td>
        <object data="Thirty.mp4" width="600px" height="300px"></object>
      </td>
    </tr>
    <tr align="center">
      <td><strong>Hiding Space (2021)</strong></td>
      <td>A short comedy cartoon animation about a monkey checking the validity of his "hiding space".</td>
      <td>
        <object data="Hiding Space.mp4" width="600px" height="300px"></object>
      </td>
    </tr>
    <tr align="center">
      <td><strong>Ordering In (2019)</strong></td>
      <td>A short comedy cartoon animation of my sister and me starting a food delivery service war.</td>
      <td>
        <object data="Ordering In.mp4" width="600px" height="300px"></object>
      </td>
    </tr>
  </table>
</br>
</br>
</br>

  <hr size="3" noshade></br>
  <button class="btn" onclick="window.location.href='index.html';">
    Home
  </button></br>
    <p style="color:white" align="center"><em>Copyright © 2022 | Gabriel J. Fields | All Rights Reserved.</em></p>
</body>

</html>
