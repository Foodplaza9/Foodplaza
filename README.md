# Foodplaza<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Plaza</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #ff6347;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .hero {
            text-align: center;
            margin-bottom: 40px;
        }
        .hero img {
            max-width: 100%;
            border-radius: 10px;
        }
        .buttons {
            text-align: center;
            margin-top: 20px;
        }
        .buttons a {
            text-decoration: none;
            color: white;
            background-color: #ff6347;
            padding: 10px 20px;
            margin: 5px;
            border-radius: 5px;
            transition: 0.3s;
        }
        .buttons a:hover {
            background-color: #e5533d;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Food Plaza</h1>
        <p>Your ultimate destination for delicious food in Yerevan!</p>
    </header>

    <div class="container">
        <div class="hero">
            <img src="https://via.placeholder.com/1000x400" alt="Food Plaza">
            <h2>Order Your Favorite Dishes Now!</h2>
            <p>Enjoy a wide variety of cuisines, freshly made and delivered to your doorstep.</p>
        </div>

        <div class="buttons">
            <a href="#menu">View Menu</a>
            <a href="#delivery">Order Now</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Food Plaza. All rights reserved. | <a href="mailto:info@foodplaza.am" style="color: #ff6347;">Contact Us</a></p>
    </footer>
</body>
</html>