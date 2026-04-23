<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to My Web Page</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1rem 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        nav h1 {
            font-size: 1.8rem;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
            transition: opacity 0.3s;
        }

        nav a:hover {
            opacity: 0.8;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .hero {
            text-align: center;
            padding: 4rem 2rem;
            background: white;
            border-radius: 8px;
            margin-bottom: 2rem;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: #667eea;
        }

        .hero p {
            font-size: 1.1rem;
            color: #666;
            margin-bottom: 2rem;
        }

        .btn {
            display: inline-block;
            background-color: #667eea;
            color: white;
            padding: 0.8rem 2rem;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            text-decoration: none;
            font-size: 1rem;
            transition: background-color 0.3s;
        }

        .btn:hover {
            background-color: #764ba2;
        }

        .content-section {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            margin-bottom: 2rem;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .content-section h3 {
            color: #667eea;
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 3rem;
        }

        footer p {
            margin: 0;
        }

        @media (max-width: 768px) {
            nav ul {
                gap: 1rem;
                font-size: 0.9rem;
            }

            .hero h2 {
                font-size: 1.8rem;
            }

            .container {
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <h1>MyWebPage</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main class="container">
        <section id="home" class="hero">
            <h2>Welcome to My Web Page</h2>
            <p>This is a modern, responsive HTML web page built from scratch.</p>
            <button class="btn">Get Started</button>
        </section>

        <section id="about" class="content-section">
            <h3>About Us</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. This is a sample web page to get you started.</p>
        </section>

        <section id="services" class="content-section">
            <h3>Our Services</h3>
            <p>We offer a variety of services including:</p>
            <ul style="margin-left: 2rem; margin-top: 1rem;">
                <li>Web Design</li>
                <li>Web Development</li>
                <li>Responsive Design</li>
                <li>SEO Optimization</li>
            </ul>
        </section>

        <section id="contact" class="content-section">
            <h3>Contact Us</h3>
            <p>Email: <a href="mailto:contact@example.com" style="color: #667eea;">contact@example.com</a></p>
            <p>Phone: <a href="tel:+1234567890" style="color: #667eea;">+1 (234) 567-890</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 MyWebPage. All rights reserved.</p>
    </footer>
</body>
</html># Springs-
Lets build 
