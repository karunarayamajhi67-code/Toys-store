<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toy Shop</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f4f4f4;
        }

        header {
            background: #ff6f61;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav {
            background: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #ff6f61;
        }

        .container {
            padding: 20px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }

        .card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
        }

        .card h3 {
            margin: 10px 0;
        }

        .card p {
            color: #555;
        }

        .btn {
            display: inline-block;
            padding: 8px 12px;
            background: #ff6f61;
            color: white;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 10px;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>🧸 Happy Toy Shop</h1>
    <p>Best Toys for Kids</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Toys</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
</nav>

<div class="container">
    <h2>Our Toys</h2>

    <div class="products">
        <div class="card">
            <img src="https://via.placeholder.com/200" alt="Toy Car">
            <h3>Toy Car</h3>
            <p>Price: Rs. 500</p>
            <a href="#" class="btn">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/200" alt="Doll">
            <h3>Doll</h3>
            <p>Price: Rs. 700</p>
            <a href="#" class="btn">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/200" alt="Teddy Bear">
            <h3>Teddy Bear</h3>
            <p>Price: Rs. 900</p>
            <a href="#" class="btn">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/200" alt="Puzzle">
            <h3>Puzzle Game</h3>
            <p>Price: Rs. 400</p>
            <a href="#" class="btn">Buy Now</a>
        </div>
    </div>
</div>

<footer>
    <p>© 2026 Happy Toy Shop | Made by You</p>
</footer>

</body>
</html>
