<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>1 of 1 Society</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">1 of 1 Society</div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="shop.html">Shop</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
        <div class="search-cart">
            <input type="text" placeholder="Search">
            <a href="cart.html">Cart</a>
        </div>
    </header>
    <main>
        <section class="hero">
            <img src="hero-image.jpg" alt="Latest Collection">
            <h1>Unique Pieces for Unique People</h1>
            <a href="shop.html" class="button">Shop Now</a>
        </section>
        <section class="featured-collection">
            <h2>Featured Collection</h2>
            <div class="product-grid">
                <!-- Example Product -->
                <div class="product">
                    <img src="product1.jpg" alt="Product Name">
                    <h3>Product Name</h3>
                    <p>$50.00</p>
                    <a href="product.html" class="button">Quick View</a>
                </div>
                <!-- Repeat for other products -->
            </div>
        </section>
        <section class="about-us">
            <h2>About Us</h2>
            <p>Our mission is to provide unique, high-quality clothing that stands out.</p>
            <a href="about.html" class="button">Learn More</a>
        </section>
        <section class="testimonials">
            <h2>Customer Testimonials</h2>
            <div class="testimonial-carousel">
                <!-- Example Testimonial -->
                <div class="testimonial">
                    <p>"Amazing quality and unique designs!" - Customer Name</p>
                </div>
                <!-- Repeat for other testimonials -->
            </div>
        </section>
        <section class="newsletter">
            <h2>Join the 1 of 1 Society</h2>
            <form>
                <input type="email" placeholder="Your email">
                <button type="submit">Subscribe</button>
            </form>
        </section>
    </main>
    <footer>
        <ul>
            <li><a href="shop.html">Shop</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="privacy.html">Privacy Policy</a></li>
            <li><a href="terms.html">Terms of Service</a></li>
        </ul>
        <div class="social-media">
            <a href="#">Instagram</a>
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
        </div>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #f8f8f8;
}

header .logo {
    font-size: 24px;
    font-weight: bold;
}

header nav ul {
    list-style: none;
    display: flex;
    gap: 15px;
}

header nav ul li {
    margin: 0;
}

header nav ul li a {
    text-decoration: none;
    color: #333;
}

header .search-cart {
    display: flex;
    gap: 10px;
}

header .search-cart input {
    padding: 5px;
}

main {
    padding: 20px;
}

.hero {
    text-align: center;
    background-color: #eee;
    padding: 50px 20px;
}

.hero img {
    max-width: 100%;
    height: auto;
}

.hero h1 {
    margin: 20px 0;
}

.hero .button {
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    text-decoration: none;
}

.featured-collection, .about-us, .testimonials, .newsletter {
    margin: 40px 0;
}

.featured-collection h2, .about-us h2, .testimonials h2, .newsletter h2 {
    margin-bottom: 20px;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.product {
    text-align: center;
    border: 1px solid #ddd;
    padding: 10px;
}

.product img {
    max-width: 100%;
    height: auto;
}

.product h3 {
    margin: 10px 0;
}

.product p {
    margin: 10px 0;
}

.product .button {
    padding: 5px 10px;
    background-color: #333;
    color: #fff;
    text-decoration: none;
}

.about-us p {
    max-width: 600px;
    margin: 0 auto;
}

.testimonial-carousel {
    display: flex;
    overflow-x: scroll;
    gap: 20px;
}

.testimonial {
    flex: 0 0 300px;
    background-color: #f8f8f8;
    padding: 20px;
    border: 1px solid #ddd;
}

.newsletter form {
    display: flex;
    justify-content: center;
    gap: 10px;
}

.newsletter input {
    padding: 10px;
}

.newsletter button {
    padding: 10px;
    background-color: #333;
    color: #fff;
    border: none;
}

footer {
    background-color: #f8f8f8;
    padding: 20px;
    text-align: center;
}

footer ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

footer ul li a {
    text-decoration: none;
    color: #333;
}

footer .social-media {
    margin-top: 20px;
}

footer .social-media a {
    margin: 0 10px;
    text-decoration: none;
    color: #333;
}
