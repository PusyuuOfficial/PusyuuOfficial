##test code.

<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width">
<title>プシューページ</title>
<style>
body {
margin: 0;
padding: 0;
}

body {
  opacity: 0;
  transform: translateY(50px);
  animation-name: fadeInAnimation;
  animation-duration: 1s;
  animation-delay: 0.5s;
  animation-fill-mode: forwards;
}

@keyframes fadeInAnimation {
  0% {
    opacity: 0;
    transform: translateY(50px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}

.header {
  background-color: #00ffff;
}

/* nav */
.nav {
    position: relative;
}
.nav_ul > li{
    display: inline-block;
}
.nav_ul > li > a{
    padding: 15px 30px;
    display: block;
    font-size: 0.8em;
    text-transform: uppercase;
    letter-spacing: .2em;
}
.nav_ul > li > span{
    margin-left: 1.2em;
}
.nav_ul > li:hover > a{
    background-color: #efefef;
    color: #444;
}
 
/* Submenu */
 
.nav_ul li .nav_sub_ul {
    position: absolute;
    top: 55px;
    left: 0;
}
.nav_ul li .nav_sub_ul li{
    display: block;
}
.nav_ul li .nav_sub_ul li a{
    background-color: #efefef;
    color: #444;
    width: auto;
}
.nav_ul li .nav_sub_ul li a:hover{
    background-color: #ddd;
}
.nav .nav_ul li .nav_sub_ul {
  display: none;
}
.nav .nav_ul li:hover .nav_sub_ul {
  display: block;
}

</style>
</head>
<body>
<header class="header">
<h1>プシューページ</h1>
<nav class="nav">
<ul class="nav_ul">
<li><a href="">サブメニュー</a>
<ul class="nav_sub_ul">
<li><a href="">SNS</a></li>
<li><a href="">TCP</a></li>
<li><a href="">OFF</a></li>
</ul>
</li>
<li><a href="">SNS</a></li>
<li><a href="">TCP</a></li>
<li><a href="">OFF</a></li>
</ul>
</nav>
</header>
<main class="main">
</main>
<footer class="footer">
</footer>
</body>
</html>
