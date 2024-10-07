<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Business Website</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f4f8;
            color: #333;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #1d2671, #c33764);
            color: white;
            padding: 40px 0;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 3.5em;
            font-weight: bold;
            letter-spacing: 2px;
        }

        /* Navigation */
        nav {
            background-color: #222;
            padding: 15px;
            text-align: center;
        }

        nav ul {
            list-style: none;
        }

        nav ul li {
            display: inline-block;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            font-weight: bold;
            padding: 10px 20px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover {
            background-color: #ff5722;
        }

        /* Hero Section */
        .hero {
            background: url('https://source.unsplash.com/1600x900/?tech') no-repeat center center/cover;
            height: 85vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            position: relative;
            box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.3);
        }

        .hero h2 {
            font-size: 3.5em;
            font-weight: bold;
            text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.7);
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.4);
        }

        .hero h2 {
            position: relative;
            z-index: 2;
        }

        /* Sections */
        section {
            padding: 80px 20px;
            text-align: center;
        }

        section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #333;
        }

        /* Services */
        .services {
            background: #fff;
            padding: 80px 20px;
        }

        .service {
            background: #f4f4f9;
            border-radius: 10px;
            margin: 20px;
            padding: 30px;
            display: inline-block;
            width: 300px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
        }

        .service:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 25px rgba(0, 0, 0, 0.2);
        }

        .service h3 {
            color: #c33764;
            font-size: 1.8em;
            margin-bottom: 10px;
        }

        /* Testimonials */
        .testimonials {
            background: linear-gradient(135deg, #ff6f61, #d24d57);
            color: white;
        }

        .testimonial {
            background: rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            margin: 20px auto;
            padding: 20px;
            width: 80%;
            max-width: 300px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .testimonial:hover {
            transform: translateY(-10px);
        }

        .testimonial strong {
            color: white;
            font-size: 1.2em;
        }

        /* Contact Section */
        .contact {
            background-color: #f9f9f9;
        }

        .contact form {
            background: white;
            max-width: 600px;
            margin: 0 auto;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }

        .contact input, .contact textarea {
            width: 100%;
            padding: 15px;
            margin-bottom: 15px;
            border: 2px solid #ddd;
            border-radius: 5px;
        }

        .contact button {
            padding: 15px 30px;
            background-color: #1d2671;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1.1em;
            transition: background-color 0.3s ease;
        }

        .contact button:hover {
            background-color: #c33764;
        }

        /* Footer */
        footer {
            background-color: #222;
            color: white;
            padding: 40px 0;
            align:center;
        }

        .social-links a {
            color: white;
            margin: 0 15px;
            font-size: 1.5em;
            transition: color 0.3s ease;
        }

        .social-links a:hover {
            color: #ff5722;
        }

        @media (max-width: 768px) {
            .services .service, .testimonials .testimonial {
                width: 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Modern Business</h1>
</header>

<nav>
    <ul>
        <li><a href="#services">Services</a></li>
        <li><a href="#testimonials">Testimonials</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<section class="hero">
    <h2>Muhammad Hamza <br> Gulzaib Colony Samnabad Lahore</h2>
</section>

<section class="services" id="services">
    <h2>Our Services</h2>
    <div class="service">
        <h3>Web Development</h3>
        <p>Building responsive and functional websites tailored to your business needs.</p>
    </div>
    <div class="service">
        <h3>Brand Identity</h3>
        <p>Creating impactful logos and brand assets to make your business stand out.</p>
    </div>
    <div class="service">
        <h3>SEO Optimization</h3>
        <p>Enhancing your online presence with powerful SEO strategies.</p>
    </div>
</section>

<section class="testimonials" id="testimonials">
    <h2>What Our Clients Say</h2>
    <div class="testimonial">
        <strong>Ahmad Qureshii</strong>
        <p>"Their web development services were top-notch! Highly recommended."</p>
    </div>
    <div class="testimonial">
        <strong>Rana Zuhaib</strong>
        <p>"Excellent design work, our brand now stands out thanks to them."</p>
    </div>
</section>

<section class="contact" id="contact">
    <h2>Get in Touch</h2>
    <form action="send_email.php" method="POST">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
    </form>
</section>

<footer align="center">
    <p>&copy; 2024 Modern Business. All rights reserved.</p>
    <div class="social-links">
        <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook-f"></i></a>
        <a href="https://twitter.com" target="_blank"><i class="fab fa-twitter"></i></a>
        <a href="https://linkedin.com" target="_blank"><i class="fab fa-linkedin"></i></a>
