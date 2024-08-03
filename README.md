<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 10px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        .hero {
            background-image: url('your-image.jpg');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
        }
        .hero h1 {
            font-size: 3em;
            margin: 0;
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        .content h2 {
            margin-top: 0;
        }
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        .menu-item {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 10px;
            padding: 10px;
            width: 200px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .menu-item h3 {
            margin: 0;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Restaurant Name</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Menu</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <div class="hero">
        <h1>Welcome to Our Restaurant</h1>
    </div>

    <div class="content">
        <h2>About Us</h2>
        <p>Our restaurant offers the finest dishes made from the freshest ingredients. Come enjoy a delightful dining experience with us.</p>
    </div>

    <div class="content">
        <h2>Our Menu</h2>
        <div class="menu">
            <div class="menu-item">
                <h3>Dish Name 1</h3>
                <p>Description of the dish.</p>
                <p><strong>$10.00</strong></p>
            </div>
            <div class="menu-item">
                <h3>Dish Name 2</h3>
                <p>Description of the dish.</p>
                <p><strong>$12.00</strong></p>
            </div>
            <div class="menu-item">
                <h3>Dish Name 3</h3>
                <p>Description of the dish.</p>
                <p><strong>$15.00</strong></p>
            </div>
        </div>
    </div>

    <div class="content">
        <h2>Contact Us</h2>
        <p>1234 Street Name, City, State, 12345</p>
        <p>Phone: (123) 456-7890</p>
        <p>Email: contact@restaurant.com</p>
    </div>

    <footer>
        <p>&copy; 2024 Restaurant Name. All rights reserved.</p>
    </footer>

</body>
</html>

