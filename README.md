<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A passionate web developer's personal portfolio">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>

    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <div class="container">
            <h1>Hi! I'm BRIAN NGUGI</h1>
            <img src="https://media-mba2-1.cdn.whatsapp.net/v/t61.24694-24/467303764_1357241355638248_3093034481692081317_n.jpg?ccb=11-4&oh=01_Q5AaIb3wZ22yyUxHvtaR7Nf_NYGxJaDkqZaJz480mpYdwNnT&oe=67FC8194&_nc_sid=5e03e0&_nc_cat=104" alt="Your Photo" class="profile-pic">
            <p>I am a passionate web developer with experience in front-end and back-end development. My focus is on creating functional, intuitive, and visually appealing websites. I believe in the power of good design and efficient code.</p>
        </div>
    </section>

    <section id="skills">
        <div class="container">
            <h2>Skills</h2>
            <p>Programming Languages:</p>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
                <li>Python</li>
                <li>React</li>
                <li>Node.js</li>
            </ul>
        </div>
    </section>

    <section id="education">
        <div class="container">
            <h2>Educational Background</h2>
            <p>I hold a degree in Civil Engineering from The University Of Nairobi.</p>
            <a href="c:\Users\BRAYO\Desktop\Brian Kamanu CV.pdf" download>Download My CV</a>
        </div>
    </section>

    <section id="interests">
        <div class="container">
            <h2>Interests</h2>
            <p>Web Development: I love building responsive and dynamic websites.</p>
            <p>Tech Innovations: I'm excited about the latest trends in AI, machine learning, and cloud computing.</p>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1</h3>
                <p>This project is about building a responsive portfolio website from scratch.</p>
                <a href="https://github.com/yourusername/project1">View Project</a>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>This project demonstrates my skills in building a dynamic to-do app using React.</p>
                <a href="https://github.com/yourusername/project2">View Project</a>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <form action="mailto:youremail@example.com" method="POST" enctype="text/plain">
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 BRIAN NGUGI. All rights reserved.</p>
        </div>
    </footer>

</body>

</html>

css styles below
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

/* Header Navigation */
header {
    background: #333;
    color: #fff;
    padding: 20px;
}

nav ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

nav ul li a:hover {
    color: #ff6347;
}

/* Section Styling */
section {
    padding: 60px 0;
    text-align: center;
}

h1, h2 {
    color: #333;
}

/* About Section */
#about .profile-pic {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    object-fit: cover;
    margin-top: 20px;
}

/* Skills Section */
#skills ul {
    list-style-type: none;
    padding: 0;
}

#skills li {
    display: inline;
    margin: 5px 15px;
    font-size: 1.2em;
    color: #555;
}

/* Projects Section */
#projects .project {
    margin: 20px 0;
}

#projects a {
    color: #ff6347;
    text-decoration: none;
}

#projects a:hover {
    text-decoration: underline;
}

/* Contact Form */
form {
    display: grid;
    gap: 15px;
    max-width: 500px;
    margin: 0 auto;
}

form input, form textarea {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1em;
}

form button {
    padding: 12px 20px;
    background-color: #ff6347;
    color: #fff;
    border: none;
    border-radius: 5px;
    font-size: 1.2em;
}

form button:hover {
    background-color: #ff4500;
}

/* Footer */
footer {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

