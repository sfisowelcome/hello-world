<!doctype html>
<html lang="eng">
<head>
<meta charset="utf-8">
<meta name="description" content="#">
<meta name="keywords" content="#">
<link rel="stylesheet" href="trial.css">
 
<title>home made</title>
</head>
<body>
<header>
<img src="" alt="" height="50" width="50">
<h3 class="blue">welcomes ways</h3>
<p class="blue"> habbits never seems so blissful homies</p>
</header>
<main>
<nav id="nav_list">
<ul>
<li><a href="home">home</a></li>
<li><a href="adventure">adventure</a></li>
<li><a href="interest">interest's</a></li>
<li><a href="contact">contact us</a></li>
</ul>
</nav><br><br>


<form name="email_form" action="sendmail.php" method="post">

<input type="text" name="firstname" id="firstname" accesskey="f">
<label for="firstname"> <u>f</u>irst name:</label><br>
<input type="text" name="lastname" id="lastname" accesskey="l">
<label for="lastname"><u>l</u>ast name:</label><br>
<input type="text" name="address" id="address" accesskey="a" >
<label for="address"><u>a</u>ddress:</label><br>
<input type="text" name="city" id="city" accesskey="c">
<label for="city"><u>c</u>ity:</label><br>
<input type="text" name="phone" id="state"  pattern="\d{3}[\-]\d{3}[\-]\d{4}" tittle="put it on the required format">
<label for="phone"><u>phone:</label><br>
<input type="text" name="zip" id="zip" accesskey="z" autocomplete="off" pattern="\d{5}([\-]\d{4})?" tittle="must be 9999 or 99999-9999">
<label for="zip"><u>z</u>ip code:</label><br>
<input type="submit" name="register" id="button" value="register">
<input type="reset" name="reset" id="reset" value="reset">
<div>

<p>our search options</p>
<label for="link">search options</label>
<input type="url" name="link" id="link" list="links">
<datalist id="links">
<option value="http:www.google.com/" label="google">
<option value="http:www.yahoo.com/" label="yahoo">
<option value="http:www.bing.com/" label="bing">
<option value="http:www.dogpile.com/" label="dogpile">
</datalist><br>

<input type="submit" name="submit" value="submit survey">





</form>








</main><br><br>
<footer>
<p class="right">&copyrights welcomes fun 2021</p>
</footer>
</body>
</html>
