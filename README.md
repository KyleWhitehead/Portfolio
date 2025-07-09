<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kyle Whitehead | Web Designer</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header class="hero">
        <h1>Kyle Whitehead</h1>
        <p class="title">Professional Web Designer</p>
        <span class="tagline">Building modern, responsive websites with HTML & CSS</span>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>
                I’m a dedicated web designer specializing in creating clean, user-friendly interfaces with HTML and CSS. My focus is on delivering professional, responsive solutions tailored to each client’s needs.
            </p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <div class="project-list">
                <div class="project">
                    <img src="project1.jpg" alt="Project 1 Screenshot">
                    <h3>Business Landing Page</h3>
                    <p>Designed and coded a responsive landing page for a small business. Features include interactive forms and mobile-first layout.</p>
                    <a href="#" target="_blank">View Live</a>
                </div>
                <div class="project">
                    <img src="project2.jpg" alt="Project 2 Screenshot">
                    <h3>Portfolio Website</h3>
                    <p>A personal portfolio site showcasing web design work, built from scratch using semantic HTML and modern CSS techniques.</p>
                    <a href="#" target="_blank">View Live</a>
                </div>
                <!-- Add more projects as needed -->
            </div>
        </section>
        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML5 & Semantic Markup</li>
                <li>CSS3 (Flexbox, Grid, Animations)</li>
                <li>Responsive Web Design</li>
                <li>UI/UX Principles</li>
                <li>Design Tools: Figma, Adobe XD</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <form action="mailto:kylewhitehead0033@yahoo.com." method="POST" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Send</button>
            </form>
            <p>Or email me directly: <a href="mailto:kylewhitehead@email.com">kylewhitehead@email.com</a></p>
