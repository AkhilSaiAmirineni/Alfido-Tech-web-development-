# Alfido-Tech-web-development-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home" class="hero">
            <h1>Welcome to Our Landing Page</h1>
            <p>Your success starts here!</p>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>We are dedicated to providing the best service.</p>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <p>Explore our wide range of services designed for you.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Get in touch with us for more information.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Your Company. All rights reserved.</p>
    </footer>
</body>
</html>
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

header {
    background: #007BFF;
    color: white;
    padding: 1em 0;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background: #6c757d;
    color: white;
    padding: 60px 20px;
    text-align: center;
}

main {
    padding: 20px;
    max-width: 800px;
    margin: auto;
    background: white;
}

section {
    margin: 20px 0;
    padding: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

footer {
    text-align: center;
    padding: 20px;
    background: #007BFF;
    color: white;
}
