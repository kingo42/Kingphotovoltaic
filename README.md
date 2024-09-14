# Kingphotovoltaic
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kingsphotovoltaic - Solar Energy Solutions</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Kingsphotovoltaic</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Solar Energy Solutions</h1>
        <p>Powering homes and businesses with clean, renewable energy.</p>
        <a href="#services" class="cta-button">Learn More</a>
    </section>

    <section id="about">
        <h2>About Kingsphotovoltaic</h2>
        <p>We provide cutting-edge solar solutions that power homes and businesses in an eco-friendly way.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="service">
            <h3>Solar Panel Installation</h3>
            <p>Professional installation of high-efficiency solar panels.</p>
        </div>
        <div class="service">
            <h3>Maintenance & Support</h3>
            <p>Comprehensive maintenance and customer support services.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Address: Shop CO3 Afro Mall Plaza, Beside OGB Doors, Opp. New Site Gate, Building Materials Market, Dei Dei, Abuja</p>
        <p>Email: info@kingsphotovoltaic.com</p>
        <p>Phone: +123 456 7890</p>
    </section>

    <footer>
        <p>&copy; 2024 Kingsphotovoltaic. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    display: flex;
    justify-content: space-between;
    padding: 20px;
}

header .logo {
    font-size: 24px;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.hero {
    background-color: #2c3e50;
    color: white;
    height: 400px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.cta-button {
    background-color: #ff9900;
    padding: 10px 20px;
    color: white;
    text-decoration: none;
    margin-top: 20px;
    border-radius: 5px;
}

section {
    padding: 60px 20px;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}document.querySelector('.cta-button').addEventListener('click', function() {
    alert('Explore our solar services!');
});