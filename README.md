
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yash Modi</title>
<style>
  body, h1, h2, h3, p {
    margin: 0;
    padding: 0;
}

/* Global Styles */
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    color: #333;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

/* Header Styles */
header {
    background-color: #222;
    color: #fff;
    padding: 20px 0;
    position: fixed;
    width: 100%;
    z-index: 1000;
}

nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

/* Hero Section Styles */
#hero {
    background-image: url('hero-background.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

.hero-text {
    max-width: 600px;
    margin: 0 auto;
}

.hero-text h1 {
    font-size: 36px;
    margin-bottom: 20px;
}

.hero-text p {
    font-size: 18px;
    margin-bottom: 30px;
}

.cta-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.cta-button:hover {
    background-color: #0056b3;
}

/* About Section Styles */
#about {
    background-color: #fff;
    padding: 60px 0;
    text-align: center;
}

#about h2 {
    font-size: 32px;
    margin-bottom: 30px;
}

#about p {
    font-size: 18px;
    line-height: 1.6;
    max-width: 800px;
    margin: 0 auto;
}

/* Portfolio Section Styles */
#portfolio {
    background-color: #f5f5f5;
    padding: 60px 0;
    text-align: center;
}

#portfolio h2 {
    font-size: 32px;
    margin-bottom: 30px;
}

.project {
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin: 0 auto 30px;
    padding: 20px;
    max-width: 400px;
}

.project img {
    max-width: 100%;
    border-radius: 5px;
}

.project h3 {
    font-size: 24px;
    margin: 10px 0;
}

.project p {
    font-size: 16px;
    margin-bottom: 20px;
}

.project a {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.project a:hover {
    background-color: #0056b3;
}

/* Contact Section Styles */
#contact {
    background-color: #fff;
    padding: 60px 0;
    text-align: center;
}

#contact h2 {
    font-size: 32px;
    margin-bottom: 30px;
}

#contact p {
    font-size: 18px;
    line-height: 1.6;
    max-width: 800px;
    margin: 0 auto 30px;
}

form {
    max-width: 400px;
    margin: 0 auto;
}

form label {
    display: block;
    font-weight: bold;
    margin-bottom: 10px;
}

form input[type="text"],
form input[type="email"],
form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

form button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

form button:hover {
    background-color: #0056b3;
}

/* Footer Styles */
footer {
    background-color: #222;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}

/* Media Queries for Responsiveness */
@media screen and (max-width: 768px) {
    nav {
        flex-direction: column;
        align-items: flex-start;
    }

    .logo {
        margin-bottom: 20px;
    }

    nav ul {
        margin-top: 20px;
    }

    #hero {
        padding: 60px 0;
    }

    .hero-text {
        padding: 0 20px;
    }

    .hero-text h1 {
        font-size: 28px;
    }

    .project {
        max-width: 100%;
    }

    form {
        max-width: 100%;
    }
}
</style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">Your Name</div>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <div class="hero-text">
            <h1>Welcome to My World of Web Development</h1>
            <p>I'm passionate about creating innovative web experiences.</p>
            <a href="#portfolio" class="cta-button">View My Work</a>
        </div>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Hi, I'm Your Name, a web developer with a creative flair. I love crafting beautiful and functional websites that leave a lasting impression.</p>
    </section>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="project">
            <img src="project1.jpg" alt="Project 1">
            <h3>Project 1</h3>
            <p>Description of Project 1.</p>
            <a href="#">View Project</a>
        </div>
        <div class="project">
            <img src="project2.jpg" alt="Project 2">
            <h3>Project 2</h3>
            <p>Description of Project 2.</p>
            <a href="#">View Project</a>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Let's collaborate on your next project! Feel free to reach out to me.</p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 20XX Your Name</p>
    </footer>
</body>
</html>
