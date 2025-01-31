# tafach <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Production Business</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>My Production Business</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Welcome to Our Production Business</h2>
            <p>We specialize in high-quality production services tailored to your needs.</p>
            <a href="#services" class="btn">Explore Our Services</a>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>We are a leading production company with years of experience in delivering top-notch products and services. Our team is dedicated to ensuring customer satisfaction and excellence in every project we undertake.</p>
        </div>
    </section>

    <section id="services" class="services">
        <div class="container">
            <h2>Our Services</h2>
            <div class="service-list">
                <div class="service-item">
                    <h3>Product Manufacturing</h3>
                    <p>We offer state-of-the-art manufacturing services for a wide range of products.</p>
                </div>
                <div class="service-item">
                    <h3>Custom Solutions</h3>
                    <p>Our team can create custom solutions tailored to your specific needs.</p>
                </div>
                <div class="service-item">
                    <h3>Quality Assurance</h3>
                    <p>We ensure that every product meets the highest quality standards.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form id="contactForm">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2023 My Production Business. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
