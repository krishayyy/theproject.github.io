<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krishay Store</title>
    <style>
        body {
            font-family: "Comic Sans MS", cursive, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #f1f1f1;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        .product {
            display: inline-block;
            margin: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 200px;
        }
        .product img {
            max-width: 100%;
            border-radius: 10px;
        }
        .product h2 {
            font-size: 1.5em;
            margin: 10px 0;
        }
        .product p {
            font-size: 1em;
            color: #666;
        }
        .product button {
            padding: 10px 20px;
            font-size: 1em;
            color: white;
            background-color: #333;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .product button:hover {
            background-color: #555;
        }
        footer {
            background-color: #f1f1f1;
            padding: 10px;
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Krishay Store</h1>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
</nav>

<div class="content" id="home">
    <h2>Welcome to Krishay</h2>
    <p>Your one-stop shop for amazing products!</p>
</div>

<div class="content" id="products">
    <h2>Our Products</h2>

    <div class="product">
        <img src="https://via.placeholder.com/200" alt="Product 1">
        <h2>Product 1</h2>
        <p>Description of product 1.</p>
        <button>Add to Cart</button>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/200" alt="Product 2">
        <h2>Product 2</h2>
        <p>Description of product 2.</p>
        <button>Add to Cart</button>
    </div>
</div>

<div class="content" id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@krishay.com</p>
    <p>Phone: +123 456 7890</p>
</div>

<footer>
    <p>&copy; 2024 Krishay. All rights reserved.</p>
</footer>

</body>
</html>
