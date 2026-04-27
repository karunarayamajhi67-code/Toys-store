<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phone Shop</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f4f4f4;
        }

        header {
            background: #111;
            color: #fff;
            padding: 15px;
            text-align: center;
        }

        nav {
            background: #333;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background: #555;
        }

        .hero {
            background: url('https://via.placeholder.com/1200x400') no-repeat center/cover;
            color: white;
            padding: 80px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 40px;
        }

        .container {
            padding: 20px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .card img {
            width: 100%;
            border-radius: 10px;
        }

        .card h3 {
            margin: 10px 0;
        }

        .price {
            color: green;
            font-weight: bold;
        }

        .btn {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background: #111;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }

        .btn:hover {
            background: #444;
        }

        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>My Phone Shop</h1>
    <p>Best Deals on Smartphones</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Contact</a>
</nav>

<section class="hero">
    <h1>Latest Smartphones</h1>
    <p>Buy the best phones at affordable prices</p>
</section>

<div class="container">
    <h2>Our Products</h2>
    <div class="products">

        <div class="card">
            <img src="https://via.placeholder.com/200" alt="Phone">
            <h3>iPhone 15</h3>
            <p class="price">$999</p>
            <a href="#" class="btn">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/200" alt="Phone">
            <h3>Samsung Galaxy S23</h3>
            <p class="price">$850</p>
            <a href="#" class="btn">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/200" alt="Phone">
            <h3>OnePlus 11</h3>
            <p class="price">$700</p>
            <a href="#" class="btn">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/200" alt="Phone">
            <h3>Xiaomi 13</h3>
            <p class="price">$650</p>
            <a href="#" class="btn">Buy Now</a>
        </div>

    </div>
</div>

<footer>
    <p>© 2026 My Phone Shop | All Rights Reserved</p>
</footer>

</body>
</html>
