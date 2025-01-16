# montewiki.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unique Website</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: #121212;
            color: #ffffff;
            overflow-x: hidden;
        }

        /* Header Styles */
        header {
            background: linear-gradient(90deg, #ff6f61, #ff9e2c);
            color: #fff;
            text-align: center;
            padding: 20px 0;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.4);
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
            animation: glowing 2s infinite;
        }

        @keyframes glowing {
            0% { text-shadow: 0 0 5px #ff6f61, 0 0 10px #ff9e2c; }
            50% { text-shadow: 0 0 20px #ff9e2c, 0 0 40px #ff6f61; }
            100% { text-shadow: 0 0 5px #ff6f61, 0 0 10px #ff9e2c; }
        }

        /* Navigation */
        nav {
            background: #1e1e1e;
            padding: 10px 0;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #ff9e2c;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ff6f61;
        }

        /* Section Styles */
        section {
            padding: 40px 20px;
            text-align: center;
        }

        section:nth-child(odd) {
            background: #1f1f1f;
        }

        section:nth-child(even) {
            background: #292929;
        }

        section h2 {
            color: #ff9e2c;
            margin-bottom: 20px;
        }

        section p {
            font-size: 1.2rem;
            line-height: 1.6;
        }

        /* Footer Styles */
        footer {
            background: linear-gradient(90deg, #ff9e2c, #ff6f61);
            text-align: center;
            color: #fff;
            padding: 10px 0;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Your Unique Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#section1">Internet</a></li>
            <li><a href="#section2">WEB</a></li>
            <li><a href="#section3">Programmetion</a></li>
            <li><a href="#section4">Contact</a></li>
        </ul>
    </nav>
    <section id="section1">
        <h2>Home</h2>
        <p>Welcome to our unique website, where creativity meets technology.</p>
    </section>
    <section id="section2">
        <h2>About</h2>
        <p>We are dedicated to providing innovative solutions that stand out in the digital landscape.</p>
    </section>
    <section id="section3">
        <h2>Services</h2>
        <p>From web design to cutting-edge software development, we have the expertise to bring your ideas to life.</p>
    </section>
    <section id="section4">
        <h2>Contact</h2>
        <p>Have a project in mind? Get in touch with us to discuss your vision.</p>
    </section>
    <footer>
        <p>&copy; 2025 Unique Website. All rights reserved.</p>
    </footer>
</body>
</html>
