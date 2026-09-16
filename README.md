# shyftvisuals.com
Shyft Apparel is a streetwear brand built for those who embrace growth, confidence, and individuality. We create stylish, high-quality pieces designed for everyday comfort and self-expression. Make the shift, stand out, and wear your ambition with Shyft <!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Shyft Apparel</title>

<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600;700;900&display=swap" rel="stylesheet">

<style>

*{

    margin:0;

    padding:0;

    box-sizing:border-box;

    font-family:'Montserrat',sans-serif;

}

body{

    background:#0d0d0d;

    color:white;

}

header{

    position:fixed;

    width:100%;

    top:0;

    z-index:100;

    background:rgba(0,0,0,0.9);

    backdrop-filter:blur(10px);

}

nav{

    display:flex;

    justify-content:space-between;

    align-items:center;

    padding:20px 8%;

}

.logo{

    font-size:2rem;

    font-weight:900;

    letter-spacing:3px;

}

.logo span{

    color:#ffffff;

}

nav ul{

    display:flex;

    list-style:none;

    gap:30px;

}

nav a{

    text-decoration:none;

    color:white;

    transition:.3s;

}

nav a:hover{

    color:#888;

}

.hero{

    height:100vh;

    background:

    linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),

    url('https://images.unsplash.com/photo-1523398002811-999ca8dec234?auto=format&fit=crop&w=1500&q=80');

    background-size:cover;

    background-position:center;

    display:flex;

    align-items:center;

    justify-content:center;

    text-align:center;

}

.hero-content h1{

    font-size:5rem;

    font-weight:900;

    letter-spacing:5px;

}

.hero-content p{

    margin-top:15px;

    font-size:1.2rem;

    color:#ddd;

}

.btn{

    display:inline-block;

    margin-top:30px;

    padding:15px 40px;

    border:2px solid white;

    color:white;

    text-decoration:none;

    transition:.3s;

}

.btn:hover{

    background:white;

    color:black;

}

.section{

    padding:100px 8%;

}

.section-title{

    text-align:center;

    font-size:3rem;

    margin-bottom:60px;

}

.products{

    display:grid;

    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));

    gap:30px;

}

.card{

    background:#161616;

    border-radius:15px;

    overflow:hidden;

    transition:.3s;

}

.card:hover{

    transform:translateY(-10px);

}

.card img{

    width:100%;

    height:350px;

    object-fit:cover;

}

.card-content{

    padding:20px;

}

.card-content h3{

    margin-bottom:10px;

}

.price{

    color:#bdbdbd;

}

.about{

    text-align:center;

    max-width:900px;

    margin:auto;

    line-height:1.8;

    color:#d4d4d4;

}

footer{

    text-align:center;

    padding:40px;

    background:#050505;

}

.socials a{

    color:white;

    text-decoration:none;

    margin:0 10px;

}

@media(max-width:768px){

.hero-content h1{

    font-size:3rem;

}

nav ul{

    display:none;

}

}

</style>

</head>

<body>

<header>

<nav>

<div class="logo">SHYFT</div>

<ul>

<li><a href="#">Home</a></li>

<li><a href="#shop">Shop</a></li>

<li><a href="#about">About</a></li>

<li><a href="#contact">Contact</a></li>

</ul>

</nav>

</header>

<section class="hero">

<div class="hero-content">

<h1>SHYFT APPAREL</h1>

<p>Premium Streetwear. Built Different.</p>

<a href="#shop" class="btn">SHOP NOW</a>

</div>

</section>

<section class="section" id="shop">

<h2 class="section-title">New Arrivals</h2>

<div class="products">

<div class="card">

<img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?auto=format&fit=crop&w=800&q=80">

<div class="card-content">

<h3>Oversized Tee</h3>

<p class="price">$35</p>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1503341455253-b2e723bb3dbb?auto=format&fit=crop&w=800&q=80">

<div class="card-content">

<h3>Essential Hoodie</h3>

<p class="price">$60</p>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246?auto=format&fit=crop&w=800&q=80">

<div class="card-content">

<h3>Cargo Pants</h3>

<p class="price">$55</p>

</div>

</div>

</div>

</section>

<section class="section" id="about">

<h2 class="section-title">About Shyft</h2>

<div class="about">

<p>

Shyft Apparel is more than clothing. It represents movement,

ambition, and the mindset of those who refuse to stay in one place.

Every piece is designed with a clean streetwear aesthetic,

premium quality, and everyday comfort.

</p>

</div>

</section>

<section class="section" id="contact">

<h2 class="section-title">Connect With Us</h2>

<div class="about">

<p>Follow us and stay updated on new drops.</p>

<br>

<div class="socials">

<a href="#">Instagram</a>

<a href="#">TikTok</a>

<a href="#">Facebook</a>

</div>

</div>

</section>

<footer>

<p>© 2026 Shyft Apparel. All Rights Reserved.</p>

</footer>

</body>

</html>
