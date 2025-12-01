<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rio Cafe - Authentic Vegetarian Cuisine</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #fff;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .logo-text {
            font-size: 2.5em;
            font-weight: bold;
            color: #8B4513; /* A warm brown to mimic the signage wood */
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
        }
        .logo-subtitle {
            font-size: 0.8em;
            color: #D9534F; /* Red accent for the cafe feel */
            margin-top: -5px;
        }
        nav {
            margin-top: 20px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #d9534f;
            font-weight: bold;
        }
        nav a:hover {
            color: #c9302c;
        }
        .hero {
            /* Using a generic image to represent the cafe exterior/vibe */
            background-image: url('https://via.placeholder.com/1200x400?text=Rio+Cafe+Exterior+and+Vibes'); 
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.8);
            text-align: center;
            background-color: rgba(0,0,0,0.4); /* Dark overlay for text readability */
        }
        .hero h1 {
            font-size: 3em;
            margin-bottom: 5px;
        }
        .hero p {
            font-size: 1.2em;
        }
        section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        h2 {
            color: #d9534f;
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 2px solid #d9534f;
            display: inline-block;
            padding-bottom: 5px;
        }
        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .menu-item {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            border-left: 5px solid #d9534f;
        }
        .menu-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 8px;
        }
        .menu-item h3 {
            margin-top: 10px;
            color: #8B4513;
        }
        .menu-item .price {
            font-weight: bold;
            color: #333;
            float: right;
        }
        .menu-item p {
            color: #666;
            margin-bottom: 0;
        }
        .contact-info p {
            text-align: center;
            font-size: 1.1em;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        footer a {
            color: #d9534f;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo-text">RIO CAFE</div>
        <div class="logo-subtitle">Tea & Snacks | Pure Veg</div>
        <nav>
            <a href="#about">About</a>
            <a href="#menu">Menu</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero">
        <h1>Welcome to Rio Cafe</h1>
        <p>A delightful experience of Indian & Continental Flavors.</p>
    </div>

    <section id="about">
        <h2>About Us</h2>
        <p>Rio Cafe is your go-to spot for delicious, high-quality pure vegetarian food. We pride ourselves on serving a wide variety of dishes, from traditional Indian favorites like **Chola Bhatura** and **Aloo Paratha** to popular cafe items like **Pizzas**, **Chaap Tandoori**, and **Chinese Starters**.</p>
        <p>Located near Bhalla Farm Compound, Kanpur, we invite you to relax and enjoy an unforgettable meal in a cozy atmosphere.</p>
        <p><strong>Hours:</strong> Please check local listings, typically open for lunch and dinner service.</p>
    </section>

    <section id="menu">
        <h2>Our Menu Highlights</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="https://via.placeholder.com/300x200?text=Veg+Pizza+Rio+Cafe" alt="Veg Pizza"> 
                <h3>Veggie Delight Pizza <span class="price">₹110</span></h3>
                <p>Our classic thin-crust pizza, loaded with fresh vegetables and cheese. (Starting price for Margherita/Pepperoni Veg)</p>
            </div>
            <div class="menu-item">
                <img src="https://via.placeholder.com/300x200?text=Malai+Paneer+Tikka" alt="Malai Paneer Tikka">
                <h3>Malai Paneer Tikka (6 PCS) <span class="price">₹250</span></h3>
                <p>Soft paneer marinated in a creamy, mild spice mix and cooked in the tandoor. A Starters Special!</p>
            </div>
            <div class="menu-item">
                <img src="https://via.placeholder.com/300x200?text=Soya+Chaap+Tandoori" alt="Soya Chaap Tandoori">
                <h3>Soya Afgani Malai Tikka <span class="price">₹280</span></h3>
                <p>Soya Chaap marinated and roasted to perfection. A highly popular Tandoori delicacy.</p>
            </div>
            <div class="menu-item">
                <img src="https://via.placeholder.com/300x200?text=Chinese+Staters" alt="Chilli Paneer">
                <h3>Chilli Paneer Dry <span class="price">₹210</span></h3>
                <p>Crispy fried paneer tossed in a spicy and tangy sauce with peppers and onions. (From our Chinese Staters)</p>
            </div>
            <div class="menu-item">
                <img src="https://via.placeholder.com/300x200?text=Deluxe+Veg+Thali" alt="Deluxe Veg Thali">
                <h3>Deluxe Veg Thali</h3>
                <p>A wholesome and satisfying meal featuring a variety of Indian curries, bread, rice, and dessert.</p>
            </div>
            <div class="menu-item">
                <img src="https://via.placeholder.com/300x200?text=Hot+and+Sour+Soup" alt="Hot and Sour Soup">
                <h3>Hot N Sour Soup <span class="price">₹90</span></h3>
                <p>A comforting and flavorful soup to start your meal. Also available: Manchow, Sweet Corn, and more.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-info">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> Bhalla Farm Compound, Kanpur - Lucknow National Highway, Bhautikheda, Uttar Pradesh (As per Menu)</p>
        <p><strong>Website:</strong> www.riofunresorts.com</p>
        <p>Follow us for updates and specials!</p>
    </section>

    <footer>
        <p>© 2023 Rio Cafe. All rights reserved. | <a href="#top">Back to Top</a></p>
    </footer>
</body>
</html>
