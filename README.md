<!DOCTYPE html>
<html lang="en">
<head>
<title>It's Awsome</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, intial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
font-family:arial;
}
header {
background-color:red;
text-align:center;
padding:30px;
color:white;
}
nav {
float:left;
width:30%;
height:300px;
background-color:black;
padding:20px;
}
nav ul {
list-style-type:none;
}
li {
font-size:26px;
padding:15px;
}
li a {
color:red;
text-decoration:none;
}
li a:hover { 
background-color:white;
padding:5px;
}
article {
padding:20px;
float:right;
width:70%;
height:300px;
background-color:yellow;
}
section:after {
  content: "";
  display: table;
  clear: both;
  }
  footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}
@media (max-width:600px) {
nav, article {
width:100%;
height:auto;
}
}
</style>
</head>
<body>
<h2>It's Awsome</h2>
<p>this is very awsome, i will keep doing this no matter what.</p>
<header>
<h1>Let's Do This</h1>
</header>
<section>
<nav>
<ul>
<li><a href="#">London</a></li>
<li><a href="#">Paris</a></li>
<li><a href="#">Tokyo</a></li>
</ul>
</nav>
<article>
<h2>London</h2>
<p>London is the capital city of England. It is the most populous city in the  United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
<p>Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.</p>
</article>
</section>
<footer>
<h2>Keep It Up</h2>
</footer>
</body>
</html>
