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
    background-color: Grey;
    color: white;
  }

  .topnav a.active {
    background-color: Black;
    color: Grey;
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
    border: 8px solid black;
    height: 300px;
    border-radius: 50%;
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    width: 300px;
  }

  a {
    text-decoration: none;
    display: inline-block;
    padding: 10px 20px;
  }

  a:hover {
    background-color: Silver;
    color: White;
  }

  li:hover {
    background-color: none;
    color: white;
  }

  .next {
    background-color: Grey;
    color: White;
  }

  .previous {
    background-color: Grey;
    color: White;
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

  .btn {
    background-color: Grey;
    border: none;
    color: White;
    padding: 12px 16px;
    font-size: 16px;
    cursor: pointer;
  }

  /* Darker background on mouse-over */
  .btn:hover {
    background-color: silver;
    color: White;
  }

  h1 {
    color: Grey;
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

  .tblb {
    border-color: Gold;
    border-style: dashed;
  }

  table {
    border-color: Silver;
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
  <title>Gabriel J Fields Website | About Me</title>
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
      ABOUT ME
    </center>
  </h1>
  </br>
  <center>
    <img src="Introducing.gif" class="circle" alt="Hello">
  </center>
  <center></br>
    <table>
      <tr>
        <td>
          <center>
            <h2>Introduction</h2>
          </center>
        </td>
      </tr>
      <tr>
        <td>
          <p class="p2" style="text-indent: 25px;">
            <strong>M</strong>y name is Gabriel James Lee Fields. I am a pretty laid-back dude who has a good number of interests.
            I recently started my new job as a </br> Manufacturing Technician at Intel and I am extremely thankful to
            have been given the opportunity to work for such an amazing company. I </br> am new to the Semiconductor industry, and I cannot
            wait to learn as much as I can so that I may be an effective contributor to my team. My </br> goal is to move into a
            Software Development, Full Stack Web Development or Test Engineering role.

            </p2>
        </td>
      </tr>
    </table>

    <h2 align="center">Hobbies</h2>
    <table class="tblb" align="center">
      <ol type="I">
        <td>
          <li><a href="Coding&Programming.html"><strong>Coding & Programming</strong>💻</a></li>
        </td>
        <td>
          <li><a href="gaming.html"><strong>Gaming</strong>🎮</a></li>
        </td>
        <td>
          <li><a href="Film Production.html"><strong>Film Production</strong>🎥</a></li>
        </td>
        <td>
          <li><a href="music.html"><strong>Music</strong>🎸</a></li>
        </td>
        <td>
          <li><a href="modelbuilding.html"><strong>Model Building</strong>🛠</a></li>
        </td>
      </ol>
    </table></br></br>

    <h2 align="center">Leisure Interests</h2>
    <table class="tblb" align="center">
      <ol type="I">
        <td>
          <li><a href="Coding&Programming.html"><strong>Football</strong>🏈</a></li>
        </td>
        <td>
          <li><a href="gaming.html"><strong>Chess</strong>♞</a></li>
        </td>
        <td>
          <li><a href="Film Production.html"><strong>Baseball</strong>⚾</a></li>
        </td>
        <td>
          <td>
            <li><a href="Film Production.html"><strong>Star Trek</strong>🖖</a></li>
          </td>
          <td>

    </table></br></br>



      </br>
      </br>
      <hr size="3" noshade>
    </br>
    </br>

  <a href="index.html" class="previous">&laquo; Back</a>
  <a href="contactme.html" class="next">Next &raquo;</a>
  <button class="btn" onclick="window.location.href='index.html';">
    Home
  </button></br></br>

  <p style="color:white" align="center"><em>Copyright © 2022 | Gabriel J. Fields | All Rights Reserved.</em></p>


</body>


</html>
