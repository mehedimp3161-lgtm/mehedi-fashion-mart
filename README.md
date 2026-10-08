<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Mehedi Fashion Mart</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,"Noto Sans Bengali",sans-serif;
}

body{
    background:#f7f7f7;
    color:#222;
}

/* Header */
header{
    background:#111827;
    color:white;
    padding:15px 5%;
    position:sticky;
    top:0;
    z-index:1000;
}

.nav{
    max-width:1100px;
    margin:auto;
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.logo{
    font-size:22px;
    font-weight:bold;
}

.logo span{
    color:#f59e0b;
}

.menu a{
    color:white;
    text-decoration:none;
    margin-left:18px;
    font-size:14px;
}

/* Hero */
.hero{
    background:linear-gradient(135deg,#111827,#374151);
    color:white;
    padding:65px 20px;
    text-align:center;
}

.hero h1{
    font-size:38px;
    margin-bottom:15px;
}

.hero p{
    font-size:17px;
    margin-bottom:25px;
    color:#e5e7eb;
}

.btn{
    display:inline-block;
    background:#f59e0b;
    color:#111;
    padding:12px 25px;
    border-radius:7px;
    text-decoration:none;
    font-weight:bold;
}

/* Categories */
.section{
    max-width:1100px;
    margin:40px auto;
    padding:0 15px;
}

.section-title{
    text-align:center;
    margin-bottom:25px;
    font-size:27px;
}

.categories{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:15px;
}

.category{
    background:white;
    padding:25px 10px;
    text-align:center;
    border-radius:10px;
    box-shadow:0 2px 10px rgba(0,0,0,.07);
}

.category .icon{
    font-size:40px;
    margin-bottom:10px;
}

/* Products */
.products{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:18px;
}

.product{
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 2px 10px rgba(0,0,0,.08);
}

.product-img{
    height:210px;
    background:#e5e7eb;
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:55px;
}

.product-info{
    padding:15px;
}

.product h3{
    font-size:17px;
    margin-bottom:8px;
}

.price{
    color:#dc2626;
    font-size:18px;
    font-weight:bold;
    margin-bottom:12px;
}

.order-btn{
    display:block;
    background:#16a34a;
    color:white;
    text-align:center;
    padding:9px;
    border-radius:6px;
    text-decoration:none;
}

/* About */
.about{
    background:white;
    padding:30px;
    border-radius:10px;
    line-height:1.8;
}

/* Contact */
.contact{
    background:#111827;
    color:white;
    padding:40px 20px;
    text-align:center;
}

.contact p{
    margin:10px 0;
}

.contact-btn{
    display:inline-block;
    margin-top:15px;
    background:#22c55e;
    color:white;
    padding:12px 25px;
    border-radius:7px;
    text-decoration:none;
}

/* Footer */
footer{
    background:#030712;
    color:#aaa;
    text-align:center;
    padding:20px;
    font-size:14px;
}

/* Mobile */
@media(max-width:800px){
    .categories{
        grid-template-columns:repeat(2,1fr);
    }

    .products{
        grid-template-columns:repeat(2,1fr);
    }

    .hero h1{
        font-size:30px;
    }

    .menu{
        display:none;
    }
}

@media(max-width:450px){
    .products{
        grid-template-columns:1fr 1fr;
        gap:10px;
    }

    .product-img{
        height:160px;
    }

    .product-info{
        padding:10px;
    }

    .product h3{
        font-size:15px;
    }
}
</style>
</head>

<body>

<!-- Header -->
<header>
<div class="nav">

<div class="logo">
Mehedi <span>Fashion Mart</span>
</div>

<div class="menu">
<a href="#home">হোম</a>
<a href="#category">ক্যাটাগরি</a>
<a href="#products">পণ্য</a>
<a href="#about">আমাদের সম্পর্কে</a>
<a href="#contact">যোগাযোগ</a>
</div>

</div>
</header>


<!-- Hero -->
<section class="hero" id="home">

<h1>Mehedi Fashion Mart</h1>

<p>
আপনার পছন্দের পোশাক ও ফ্যাশন পণ্য<br>
সহজে অর্ডার করুন, ঘরে বসেই।
</p>

<a href="#products" class="btn">
পণ্য দেখুন
</a>

</section>


<!-- Categories -->
<section class="section" id="category">

<h2 class="section-title">
ক্যাটাগরি
</h2>

<div class="categories">

<div class="category">
<div class="icon">👔</div>
<h3>পুরুষ</h3>
</div>

<div class="category">
<div class="icon">👗</div>
<h3>নারী</h3>
</div>

<div class="category">
<div class="icon">👶</div>
<h3>শিশু</h3>
</div>

<div class="category">
<div class="icon">🛏️</div>
<h3>হোম & লাইফস্টাইল</h3>
</div>

</div>

</section>


<!-- Products -->
<section class="section" id="products">

<h2 class="section-title">
জনপ্রিয় পণ্য
</h2>

<div class="products">


<!-- Product 1 -->
<div class="product">

<div class="product-img">
👕
</div>

<div class="product-info">

<h3>Premium Men's T-Shirt</h3>

<div class="price">
৳ 550
</div>

<a class="order-btn"
href="https://wa.me/8801XXXXXXXXX">
অর্ডার করুন
</a>

</div>

</div>


<!-- Product 2 -->
<div class="product">

<div class="product-img">
👔
</div>

<div class="product-info">

<h3>Men's Casual Shirt</h3>

<div class="price">
৳ 850
</div>

<a class="order-btn"
href="https://wa.me/8801XXXXXXXXX">
অর্ডার করুন
</a>

</div>

</div>


<!-- Product 3 -->
<div class="product">

<div class="product-img">
👗
</div>

<div class="product-info">

<h3>Women's Three Piece</h3>

<div class="price">
৳ 1,250
</div>

<a class="order-btn"
href="https://wa.me/8801XXXXXXXXX">
অর্ডার করুন
</a>

</div>

</div>


<!-- Product 4 -->
<div class="product">

<div class="product-img">
🧕
</div>

<div class="product-info">

<h3>Half Silk Saree</h3>

<div class="price">
৳ 1,100
</div>

<a class="order-btn"
href="https://wa.me/8801XXXXXXXXX">
অর্ডার করুন
</a>

</div>

</div>


<!-- Product 5 -->
<div class="product">

<div class="product-img">
👶
</div>

<div class="product-info">

<h3>Baby Dress</h3>

<div class="price">
৳ 650
</div>

<a class="order-btn"
href="https://wa.me/8801XXXXXXXXX">
অর্ডার করুন
</a>

</div>

</div>


<!-- Product 6 -->
<div class="product">

<div class="product-img">
🏏
</div>

<div class="product-info">

<h3>Sports Jersey</h3>

<div class="price">
৳ 450
</div>

<a class="order-btn"
href="https://wa.me/8801XXXXXXXXX">
অর্ডার করুন
</a>

</div>

</div>


<!-- Product 7 -->
<div class="product">

<div class="product-img">
🛏️
</div>

<div class="product-info">

<h3>Premium Bedsheet</h3>

<div class="price">
৳ 950
</div>

<a class="order-btn"
href="https://wa.me/8801XXXXXXXXX">
অর্ডার করুন
</a>

</div>

</div>


<!-- Product 8 -->
<div class="product">

<div class="product-img">
👚
</div>

<div class="product-info">

<h3>Couple Dress</h3>

<div class="price">
৳ 1,650
</div>

<a class="order-btn"
href="https://wa.me/8801XXXXXXXXX">
অর্ডার করুন
</a>

</div>

</div>

</div>

</section>


<!-- About -->
<section class="section" id="about">

<h2 class="section-title">
আমাদের সম্পর্কে
</h2>

<div class="about">

<p>
<b>Mehedi Fashion Mart</b> একটি অনলাইন ফ্যাশন শপ।
আমরা পুরুষ, নারী ও শিশুদের জন্য বিভিন্ন ধরনের
পোশাক এবং প্রয়োজনীয় ফ্যাশন পণ্য সরবরাহ করি।
</p>

<p>
আমাদের লক্ষ্য হলো ভালো মানের পণ্য সহজে
ক্রেতার কাছে পৌঁছে দেওয়া এবং সৎ ও
বিশ্বস্ত অনলাইন শপ হিসেবে গড়ে ওঠা।
</p>

</div>

</section>


<!-- Contact -->
<section class="contact" id="contact">

<h2>অর্ডার বা যোগাযোগ</h2>

<p>📱 মোবাইল: 01XXXXXXXXX</p>

<p>🚚 সারাদেশে কুরিয়ার ডেলিভারি</p>

<p>💵 Cash on Delivery Available</p>

<a class="contact-btn"
href="https://wa.me/8801XXXXXXXXX">
WhatsApp এ যোগাযোগ করুন
</a>

</section>


<!-- Footer -->
<footer>

<p>
© 2026 Mehedi Fashion Mart
</p>

<p>
All Rights Reserved.
</p>

</footer>

</body>
</html> mehedi-fashion-mart
