
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Home Page</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #947f7f;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    text-decoration: none;
    color: #fff;
}

main {
    padding: 20px;
}

.hero {
    background-image: url('hero-image.jpg'); /* Add an attractive background image */
    background-size: cover;
    text-align: center;
    padding: 100px 0;
    color: #fff;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #ff6600;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 20px;
}

.features {
    display: flex;
    justify-content: space-between;
    padding: 20px 0;
}

.feature {
    flex-basis: 30%;
    text-align: center;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
}

    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="C:\Users\harsh\project1.html">Home</a></li>
                <li><a href="C:\Users\harsh\About.html">About</a></li>
                <!-- <li><a href="#">Services</a></li> -->
                <li><a href="C:\Users\harsh\Portfolio.html">Portfolio</a></li>
                <li><a href="C:\Users\harsh\Contact Details.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>Welcome to Our Website</h1>
            <p>Your one-stop destination for all your needs.</p>
            <a href="#" class="cta-button">Learn More</a>
        </section>

        <section class="features">
            <div class="feature">
                <h2>Quality Products</h2>
                <p>We offer the finest products to our customers.</p>
            </div>
            <div class="feature">
                <h2>Expert Services</h2>
                <p>Our team of experts is ready to assist you.</p>
            </div>
            <div class="feature">
                <h2>Customer Satisfaction</h2>
                <p>Your satisfaction is our top priority.</p>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Your Company Name</p>
    </footer>
</body>
</html>
