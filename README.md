# PORTFOLIO
Hi here I am Web developer.
My self SUKHMAN SINGH SANDHU
<!DOCTYPE html>
<html lang="en">
<head>
<title>CSS Template</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>

<header>
  <h4><a href ="main.html">ABOUT</a>
	<a href ="resume.html">RESUME</a>
	<a href ="portfolio.html">PORTFOLIO</a>
	<a href ="services.html">SERVICES</a>
	<a href ="contact.html">CONTACT</a>
</h4>
</header>

<section>
  <nav>
    <img src="sukh.jpeg" width="250" height="270" style="vertical-align:middle;float:right,margin:0px 50px">
  </nav>
  
  <article>
    <h1>MY self</h1>
    <p>I Sukhman singh sandhu .I am from India and came to canada for my higher studies and explore my career as as computer professional .Check out my resume to find out more...</p>
	<p>I am thankful to my tutor who guide me and helps me in my studies.</p>
     </article>
</section>

<footer>
  <p><b><i>Sukhman Singh Sandhu </i></b><br><br>
    <a href="mailto:sandhusukhmandeep60@gmail.com"><i>sandhusukhmandeep60@gmail.com </i><br><br><br>

<a href ="main.html">ABOUT</a>
	<a href ="resume.html">RESUME</a>
	<a href ="portfolio.html">PORTFOLIO</a>
	<a href ="services.html">SERVICES</a>
	<a href ="contact.html">CONTACT</a></p>
<br><br><br><br>2021 sukhman.ca - All Rights Reserved
</footer>

</body>
</html>

