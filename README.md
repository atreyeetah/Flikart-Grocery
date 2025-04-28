# Flikart-Grocery
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flipkart Deals - Best Offers for You!</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Flipkart Affiliate Deals</h1>
        <nav>
            <a href="#products">Products</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="hero">
        <h2>Best Flipkart Offers, Handpicked for You!</h2>
        <p>Shop smarter and save more. Every purchase helps us too!</p>
        <a href="#products" class="btn">Explore Now</a>
    </section>

    <section id="products">
        <h2>Featured Products</h2>
        <div class="product-grid">

            <!-- Product 1 -->
            <div class="product-card">
                <img src="https://via.placeholder.com/200" alt="Product 1">
                <h3>Product Name 1</h3>
                <p>Short description of the product.</p>
                <a href="YOUR_FLIPKART_AFFILIATE_LINK_1" target="_blank" class="btn">Buy on Flipkart</a>
            </div>

            <!-- Product 2 -->
            <div class="product-card">
                <img src="https://via.placeholder.com/200" alt="Product 2">
                <h3>Product Name 2</h3>
                <p>Short description of the product.</p>
                <a href="YOUR_FLIPKART_AFFILIATE_LINK_2" target="_blank" class="btn">Buy on Flipkart</a>
            </div>

            <!-- Add more products similarly -->

        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We bring you the best deals from Flipkart. All the links are affiliate links which help us earn a small commission at no extra cost to you.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Have any questions? <br>Email us at: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
    </section>

    <footer>
        <p>© 2025 Flipkart Affiliate Site. All rights reserved.</p>
    </footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background: #2874f0;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

#hero {
    background: #f1f1f1;
    padding: 2rem;
    text-align: center;
}

.btn {
    display: inline-block;
    background: #2874f0;
    color: white;
    padding: 0.5rem 1rem;
    margin-top: 1rem;
    text-decoration: none;
    border-radius: 5px;
}

#products {
    padding: 2rem;
    background: #fff;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
}

.product-card {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 1rem;
    text-align: center;
}

.product-card img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

#about, #contact {
    padding: 2rem;
    background: #f9f9f9;
    text-align: center;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem;
}
