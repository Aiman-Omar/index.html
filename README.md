# Sonder Clothing Website

Welcome to Sonder Clothing, your one-stop shop for the latest in fashion.

## Directory Structure


## HTML - `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sonder Clothing</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main id="home">
        <h1>Welcome to Sonder Clothing</h1>
        <p>Your one-stop shop for the latest in fashion.</p>
    </main>
    <section id="shop">
        <h2>Shop Our Collection</h2>
        <div class="product-grid">
            <!-- Products will be dynamically added here -->
        </div>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>Learn more about our brand and our mission.</p>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Get in touch with us for any queries or feedback.</p>
    </section>
    <footer>
        <p>&copy; 2024 Sonder Clothing. All rights reserved.</p>
    </footer>
    <script src="js/scripts.js"></script>
</body>
</html>
