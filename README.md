<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bantu Supply - About Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Welcome to Bantu Supply</h1>
        </header>
        <section class="about">
            <img src="logo.jpg" alt="Bantu Supply" class="profile-pic">
            <h2>About Bantu Supply</h2>
            <p>At Bantu Supply, we are committed to providing high-quality products and services to meet the needs of our customers. Our team is dedicated to excellence and innovation in everything we do.</p>
            <p>We specialize in offering a wide range of products sourced from trusted suppliers, ensuring quality and reliability.</p>
            <button class="btn" onclick="showMore()">Learn More</button>
        </section>
        <section class="contact">
            <h2>Contact Us</h2>
            <p>Email: <a href="mailto:info@bantusupply.com">info@bantusupply.com</a></p>
            <p>Phone: <a href="tel:+123456789">+123 456 789</a></p>
            <p>Location: Nairobi, Kenya</p>
            <button class="btn" onclick="openLinkedIn()">Visit Our LinkedIn</button>
        </section>
    </div>
    <script src="script.js"></script>
</body>
</html>

/* Styles for Bantu Supply */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    text-align: center;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 800px;
    margin: auto;
    padding: 20px;
}

header {
    background-color: #008080;
    padding: 20px;
    border-radius: 10px;
}

h1, h2 {
    color: #004d4d;
}

.about, .contact {
    background-color: #e0f7fa;
    padding: 20px;
    margin: 20px 0;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0, 128, 128, 0.3);
}

.profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 10px;
    border: 3px solid #004d4d;
}

.btn {
    background-color: #006666;
    color: #fff;
    border: none;
    padding: 10px 15px;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s;
}

.btn:hover {
    background-color: #004d4d;
}

a {
    color: #006666;
    text-decoration: none;
}

/* Scripts for Bantu Supply */
function showMore() {
    alert("Bantu Supply is dedicated to providing high-quality products and services to meet the diverse needs of our customers.");
}

function openLinkedIn() {
    window.open("https://www.linkedin.com/company/bantu-supply", "_blank");
}