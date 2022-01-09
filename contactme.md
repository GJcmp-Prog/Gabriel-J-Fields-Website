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
    border: 5px solid black;
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

  .previous {
    background-color: Grey;
    color: White;
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
    color: Grey;
    font-family: serif;
  }

  h2 {
    color: Grey;
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
  <title>Gabriel J Fields Website | Contact Me</title>
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
      CONTACT INFORMATION
    </center>
  </h1>

  <table style="width:80%" border="4" white align="center">
    <tr>
      <th>E-mail # 1</th>
      <th>E-mail # 2</th>
      <th>LinkedIn</th>
    </tr>
    <tr align="center">
      <td>Gabriel.Fields26@yahoo.com</td>
      <td>Gabe.Fields18@gmail.com</td>
      <td><strong>gabriel-fields-01423322a</strong></td>
    </tr>
    </tr>
    <tr align="center">
      <td><a href="https://login.yahoo.com/?.lang=en-US&src=homepage&activity=ybar-signin&pspid=2023538075&done=https%3A%2F%2Fwww.yahoo.com%2F&add=1"><img src="Yahoo_logo.png" height="100" width="100" align="center" alt=" Yahoo Mail Logo"></a></td>
      <td><a href="https://accounts.google.com/signin/v2/identifier?service=mail&passive=true&rm=false&continue=https%3A%2F%2Fmail.google.com%2Fmail%2F%26ogbl%2F&ss=1&scc=1&ltmpl=default&ltmplcache=2&emr=1&osid=1&flowName=GlifWebSignIn&flowEntry=ServiceLogin"><img
            src="Gmail_logo.jpg" height="100" width="100" align="center" alt=" GMail Logo"></a></td>
      <td><a href="https://www.linkedin.com/in/gabriel-fields-01423322a/"><img src="linkedIn_logo.png" height="100" width="100" align="center" alt="LinkedIn Logo"></a></td>
    </tr>
  </table>

  </br>
  </br>
  </br>
  </br>
  </br>
  </br>
  </br>
  </br>


  <a href="aboutme.html" class="previous">&laquo; Back</a>
  <button class="btn" onclick="window.location.href='index.html';">
    Home
  </button></br>
  <p style="color:white" align="center"><em>Copyright © 2022 | Gabriel J. Fields | All Rights Reserved.</em></p>
</body>

</html>
