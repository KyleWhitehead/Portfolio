<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kyle Whitehead - Frontend Developer</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Kyle Whitehead</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <img src="images/profile.jpg" alt="Your Name" class="profile-img">
            <h1>Frontend Developer</h1>
            <p class="hero-subtitle">Creating clean, responsive websites that work everywhere</p>
            <div class="hero-buttons">
                <a href="#projects" class="btn-primary">View My Work</a>
                <a href="https://github.com/yourusername" class="btn-secondary" target="_blank">GitHub Profile</a>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Detail-oriented professional transitioning from facilities management to web development. I bring proven reliability, strong work ethic, and attention to detail to creating responsive, user-friendly websites.</p>
            <p>Certified in Responsive Web Design with expertise in modern HTML5 and CSS3 practices.</p>
            
            <div class="skills">
                <h3>Skills</h3>
                <ul class="skills-list">
                    <li>HTML5</li>
                    <li>CSS3</li>
                    <li>Responsive Design</li>
                    <li>Mobile-First Development</li>
                    <li>Cross-Browser Compatibility</li>
                </ul>
            </div>
        </div>
    </section>
</body>
</html>

/* Reset and Base Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #fff;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

/* Header and Navigation */
header {
    background: #2c3e50;
    color: white;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
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

.logo {
    font-size: 1.5rem;
    font-weight: bold;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-links a {
    color: white;
    text-decoration: none;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: #3498db;
}

/* Hero Section */
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 8rem 2rem 4rem;
    text-align: center;
    margin-top: 60px;
}

.hero-content {
    max-width: 800px;
    margin: 0 auto;
}

.profile-img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 2rem;
    border: 4px solid white;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero-subtitle {
    font-size: 1.2rem;
    margin-bottom: 2rem;
    opacity: 0.9;
}

.hero-buttons {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
}

.btn-primary, .btn-secondary {
    padding: 12px 24px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: all 0.3s;
    display: inline-block;
}

.btn-primary {
    background: #e74c3c;
    color: white;
}

.btn-primary:hover {
    background: #c0392b;
    transform: translateY(-2px);
}

.btn-secondary {
    background: transparent;
    color: white;
    border: 2px solid white;
}

.btn-secondary:hover {
    background: white;
    color: #667eea;
}

/* About Section */
.about {
    padding: 4rem 0;
    background: #f8f9fa;
}

.about h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 2rem;
    color: #2c3e50;
}

.about p {
    font-size: 1.1rem;
    margin-bottom: 1.5rem;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
}

.skills {
    max-width: 800px;
    margin: 3rem auto 0;
}

.skills h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    color: #2c3e50;
}

.skills-list {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    list-style: none;
}

.skills-list li {
    background: #3498db;
    color: white;
    padding: 8px 16px;
    border-radius: 20px;
    font-size: 0.9rem;
}

/* Responsive Design */
@media (max-width: 768px) {
    .nav-links {
        display: none; /* You can add mobile menu later */
    }
    
    .hero h1 {
        font-size: 2rem;
    }
    
    .hero-subtitle {
        font-size: 1rem;
    }
    
    .hero-buttons {
        flex-direction: column;
        align-items: center;
    }
    
    .btn-primary, .btn-secondary {
        width: 200px;
    }
    
    .container {
        padding: 0 1rem;
    }
}

@media (max-width: 480px) {
    .hero {
        padding: 6rem 1rem 2rem;
    }
    
    .profile-img {
        width: 120px;
        height: 120px;
    }
}
