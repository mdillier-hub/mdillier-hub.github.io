<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f9;
        }

        /* Navigation */
        nav {
            background: #2c3e50;
            color: #fff;
            padding: 1rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        /* Hero Section */
        header {
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1497215728101-856f4ea42174?auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        /* Sections */
        section {
            padding: 4rem 2rem;
            max-width: 1100px;
            margin: auto;
        }

        h2 {
            text-align: center;
            margin-bottom: 2rem;
            font-size: 2rem;
            color: #2c3e50;
        }

        /* Project Grid */
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .project-card {
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-card h3 {
            margin-bottom: 10px;
            color: #3498db;
        }

        /* Contact Section */
        #contact {
            background: #2c3e50;
            color: white;
            text-align: center;
        }

        .social-links a {
            color: #3498db;
            margin: 0 10px;
            text-decoration: none;
            font-size: 1.2rem;
        }

        footer {
            text-align: center;
            padding: 2rem;
            font-size: 0.9rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 { font-size: 2rem; }
            nav { flex-direction: column; }
            nav ul { margin-top: 10px; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">MyBrand</div>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header>
        <h1>Hi, I'm [Your Name]</h1>
        <p>Full Stack Developer | Designer | Problem Solver</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>
            Welcome to my portfolio! I am a passionate creator dedicated to building functional 
            and beautiful digital experiences. I specialize in HTML, CSS, and JavaScript, 
            with a focus on clean code and user-centric design.
        </p>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <h3>Project One</h3>
                <p>A short description of what this project does and the technologies used to build it.</p>
            </div>
            <div class="project-card">
                <h3>Project Two</h3>
                <p>An e-commerce landing page focused on performance and accessibility.</p>
            </div>
            <div class="project-card">
                <h3>Project Three</h3>
                <p>A data visualization dashboard built using modern web frameworks.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Get In Touch</h2>
        <p>I'm currently looking for new opportunities!</p>
        <div class="social-links" style="margin-top: 20px;">
            <a href="mailto:yourname@email.com">Email Me</a>
            <a href="#">LinkedIn</a>
            <a href="#">GitHub</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 [Your Name]. All rights reserved.</p>
    </footer>

</body>
</html>
