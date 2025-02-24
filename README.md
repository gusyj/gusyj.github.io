<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gustouv Leck - About Me</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Welcome to My Page</h1>
        </header>
        <section class="about">
            <img src="profile.jpg" alt="Gustouv Leck" class="profile-pic">
            <h2>I'm Gustouv Leck</h2>
            <p>A passionate Computer Science student with a strong interest in AI, Marketing, and Game Development. I enjoy problem-solving, coding, and creating meaningful projects.</p>
            <button class="btn" onclick="showMore()">Learn More</button>
        </section>
        <section class="contact">
            <h2>Contact Me</h2>
            <p>Email: <a href="mailto:leckgustouv+instagram@gmail.com">leckgustouv+instagram@gmail.com</a></p>
            <p>Phone: <a href="tel:+447459486711">+44 7459 486711</a></p>
            <p>Location: Richmond, Surrey, UK</p>
            <button class="btn" onclick="openLinkedIn()">Visit My LinkedIn</button>
        </section>
    </div>
    <script src="script.js"></script>
</body>
</html>
/* Apply a dark background with light green highlights */
body {
    font-family: Arial, sans-serif;
    background-color: #0a0f0d;
    color: #d4f4dd;
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
    background-color: #183d2b;
    padding: 20px;
    border-radius: 10px;
}

h1, h2 {
    color: #8de4af;
}

.about, .contact {
    background-color: #12281c;
    padding: 20px;
    margin: 20px 0;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(141, 228, 175, 0.3);
}

.profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 10px;
    border: 3px solid #8de4af;
}

.btn {
    background-color: #21a179;
    color: #fff;
    border: none;
    padding: 10px 15px;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s;
}

.btn:hover {
    background-color: #178b64;
}

a {
    color: #8de4af;
    text-decoration: none;
}
// Show an alert when clicking the "Learn More" button
function showMore() {
    alert("I am a Computer Science student with a focus on AI, Data Analysis, and Game Development. Passionate about innovation and learning!");
}

// Open LinkedIn profile when button is clicked
function openLinkedIn() {
    window.open("https://www.linkedin.com/in/gustouv-leck", "_blank");
}
