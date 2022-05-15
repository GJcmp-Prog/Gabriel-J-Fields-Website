<!DOCTYPE html>
<html lang="en" dir="ltr">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
  body {
    background-image: url("BackGround.jpg");
  }

  body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
  }

  div.c {
    -webkit-text-decoration-line: underline;
    /* Chrome  */
    text-decoration-line: underline;
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
    border: 8px solid blue;
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

  .p1 {
    color: White;
    font-size: 20px;
    font-family: serif;
    font-style: normal;
  }

  .p2 {
    font-weight: 300;
    color: white;
    font-family: serif;
    font-style: normal;
    font-size: 20px;
  }

  h1 {
    color: Grey;
    font-style: normal;
  }

  h2 {
    color: Grey;
    font-family: serif;
  }

  .txt1 {
      color: Blue;
      text-decoration-line: underline;
      text-decoration-color: White ;
  }

  .txt2 {
      text-decoration-line: underline;
      text-decoration-color: blue;
  }

  .txt3 {
      color: White;
  }


  .ul {
    color: White;
    font-family: serif;
    font-size: 20px;
  }

  th {
    color: White;
    font-family: serif;
  }

  .td1 {
    color: White;
    font-family: serif;
  }

  .tblb {
    border-color: Gold;
    border-style: dashed;
  }

  .tblb2 {
    border-color: Silver;
    border-style: groove;
  }

  .footer {
    position:relative;
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
  <title>Gabriel J Fields Website | Homepage</title>
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

</br>


<div class="c">

</div>
<center>
<table>
  <tr>
    <td>
      <img src="Gabriel 5.2022.png" class="circle" alt="Gabriel Profile Picture">
    </td>
    <td>
      <h1 class="h1"> GABRIEL J FIELDS </h1>
      <p2 class="p2">
        <em>Programmer by day, Technician by night.</em>
      </p2></br></br>
      <p2 class="p2">
      <strong>Manufacturing Technician</strong> at <p1 class="txt1"><strong>Intel</strong></p1>.
    </br>
      </p2>

    </td>
  </tr>
</table>
</center>
</br>

<center>
  <p2 class="p2">
    <p2 class="txt3" style="text-indent: 25px;"><strong>H</strong></p2>ello and welcome to my personal website! Please feel free to have a look around to get a better idea of who I am on a personal
    and profressional level. <br />I hope you enjoy your visit.
  </p2>
</center> </br>
<hr size="3" noshade>
<h2 align="center">Skills</h2>
<center>
  <table style="width:80%" border="8" class="tblb2">
    <tr>
      <th>Skill</th>
      <th>Demonstration</th>
    </tr>
    <tr align="center">
      <td class="td1">Technical Assembly</td>
      <td class="td1"><strong>A</strong>s both factory lead and as a technician, I have assembled a variety of EPS </br> and HST products on the manufacturing floor
      of Intel's System Development Lab.</td>
    </tr>
    <tr align="center">
      <td class="td1">Technical Writing</td>
      <td class="td1"><strong>A</strong>s Factory lead, I have constructed a Spec for the SAP ME workflow process </br> for manufacturing technicians in
      Intel's System Development Lab. </td>
    </tr>
    <tr align="center">
      <td class="td1">Web Dev</td>
      <td class="td1"><strong>I</strong>n my personal life, I love to develop webpages and sites, such as this one.
        I first started</br> web development in Senior year of HighSchool.</td>
    </tr>
    <tr align="center">
      <td class="td1">Leadership</td>
      <td class="td1"> <strong>A</strong>s the Assistant General Manager of Jiffy Lube,  I lead my team by
      directing them based on </br>
       bay priority to ensure a fluent flow of business to get cars in and out in a timely manner. </br></br>
    <strong>A</strong>s the Manufacturing Lead of the System Developement Lab at Kelly Services, I took </br>
     on the responsibilites of timecard approvals, conducting 1-on-1 check in meetings, </br>
     and satisfying the needs and requests of my team.
    </td>
    </tr>
    <tr align="center">
      <td class="td1">Game and App Dev</td>
      <td class="td1"><strong>I</strong>n my personal life I have referenced different online sources like MDN Docs and W3schools </br>
         to get my feet wet
      in Game Develeopment. I have coded my game called <a href="file:///C:/Users/GabeF/Desktop/Programming%20Projects/GameDev%20Projects/HyperNerd%20Games/Geo/GEO%20[Space%20Racer].html">GEO [Space Racer]</a>.
    </br> The game is based on a tutorial excercise on W3schools.</td>
    </tr>
  </table>
</center></br>

</br>
</br>
</br>


<a href="aboutme.html" class="next">Next &raquo;</a></br>

<hr size="3" noshade></br>

<div class="footer">
  <p><em>Copyright © 2022 | Gabriel J. Fields | All Rights Reserved.</em></p>
</div>



</body>




</html>
