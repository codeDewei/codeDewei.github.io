project-folder/
├── index.html
├── style.css
├── images/
│   ├── profile.jpg
│   ├── project1.jpg
│   └── project2.jpg
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodeDewei Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">CodeDewei</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Welcome to My Portfolio</h1>
            <p>I'm a passionate developer specializing in web applications.</p>
            <a href="#projects" class="btn">View Projects</a>
        </div>
    </section>

    <section id="about" class="about">
        <h2>About Me</h2>
        <div class="about-content">
            <img src="images/profile.jpg" alt="Profile Picture">
            <p>
                Hello! I'm CodeDewei, a developer with a knack for creating dynamic and responsive web applications. With a strong foundation in HTML, CSS, and JavaScript, I build user-friendly interfaces and seamless user experiences.
            </p>
        </div>
    </section>

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project-cards">
            <div class="card">
                <img src="images/project1.jpg" alt="Project 1">
                <h3>YumMaze</h3>
                <p>A fun and interactive game that challenges your maze-solving skills.</p>
                <a href="https://codedewei.github.io/YumMaze" target="_blank">View Project</a>
            </div>
            <div class="card">
                <img src="images/project2.jpg" alt="Project 2">
                <h3>Project Two</h3>
                <p>A web application that streamlines task management for teams.</p>
                <a href="#" target="_blank">View Project</a>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <form action="mailto:your.email@example.com" method="post" enctype="text/plain">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 CodeDewei. All rights reserved.</p>
    </footer>
</body>
</html>
/* Reset and base styles */
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

/* Navigation */
header {
    background-color: #333;
    padding: 20px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 90%;
    margin: auto;
}

.logo {
    color: #fff;
    font-size: 24px;
    font-weight: bold;
}

.nav-links {
    list-style: none;
    display: flex;
}

.nav-links li {
    margin-left: 20px;
}

.nav-links a {
    color: #fff;
    text-decoration: none;
    font-size: 16px;
}

.nav-links a:hover {
    text-decoration: underline;
}

/* Hero Section */
.hero {
    background: url('images/hero-bg.jpg') no-repeat center center/cover;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.hero-content {
    background-color: rgba(0, 0, 0, 0.6);
    padding: 40px;
    border-radius: 10px;
}

.hero-content h1 {
    color: #fff;
    font-size: 48px;
    margin-bottom: 20px;
}

.hero-content p {
    color: #ddd;
    font-size: 20px;
    margin-bottom: 30px;
}

.btn {
    background-color: #e8491d;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.btn:hover {
    background-color: #cf3e17;
}

/* About Section */
.about {
    padding: 60px 20px;
    background-color: #fff;
    text-align: center;
}

.about-content {
    max-width: 800px;
    margin: auto;
}

.about-content img {
    width: 150px;
    border-radius: 50%;
    margin-bottom: 20px;
}

/* Projects Section */
.projects {
    padding: 60px 20px;
    background-color: #f4f4f4;
    text-align: center;
}

.project-cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-top: 40px;
}

.card {
    background-color: #fff;
    border-radius: 10px;
    width: 300px;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    text-align: left;
}

.card img {
    width: 100%;
    border-radius: 10px;
}

.card h3 {
    margin: 15px 0;
}

.card p {
    font-size: 14px;
    margin-bottom: 15px;
}

.card a {
    color: #e8491d;
    text-decoration: none;
    font-weight: bold;
}

.card a:hover {
    text-decoration: underline;
}

/* Contact Section */
.contact {
    padding: 60px 20px;
    background-color: #fff;
    text-align: center;
}

.contact form {
    max-width: 600px;
    margin: auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact input,
.contact textarea {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
}

.contact button {
    padding: 10px;
    background-color: #e8491d;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.contact button:hover {
    background-color: #cf3e17;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    margin-top: 40px;
}
