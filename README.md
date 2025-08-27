<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      line-height: 1.6;
      color: #333;
      background: #f4f4f9;
    }

    header {
      background: #333;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    header h1 {
      margin-bottom: 10px;
    }

    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    section h2 {
      margin-bottom: 20px;
      color: #444;
      text-align: center;
    }

    .about img {
      display: block;
      margin: 0 auto 20px;
      width: 150px;
      border-radius: 50%;
    }

    .skills ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }

    .skills li {
      background: #eee;
      padding: 10px 20px;
      border-radius: 20px;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project {
      background: #fff;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .project img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 10px;
    }

    .resume a {
      display: inline-block;
      background: #333;
      color: #fff;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
    }

    .contact p {
      text-align: center;
      margin: 10px 0;
    }

    footer {
      background: #222;
      color: #aaa;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>Sudhakar Chaudhary</h1>
    <p>Web Developer | Designer | Programmer</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#resume">Resume</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <img src="IMG_0001.JPG.jpg" alt="My Photo">
    <p>Hello! I am a passionate web developer skilled in HTML, CSS, and JavaScript. I love creating clean and user-friendly websites and web applications.</p>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="skills">
    <h2>My Skills</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Python</li>
      <li>React</li>
    </ul>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>My Projects</h2>
    <div class="projects">
      <div class="project">
        <img src="project1.jpg" alt="Project 1">
        <h3>Project Title 1</h3>
        <p>Brief description of the project goes here.</p>
      </div>
      <div class="project">
        <img src="project2.jpg" alt="Project 2">
        <h3>Project Title 2</h3>
        <p>Brief description of the project goes here.</p>
      </div>
    </div>
  </section>

  <!-- Resume Section -->
  <section id="resume" class="resume">
    <h2>Resume</h2>
    <p style="text-align:center;">
      <a href="resume.pdf" download>Download My Resume</a>
    </p>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Email: your.email@example.com</p>
    <p>Phone: +91 12345 67890</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Sudhakar Chaudhary. All rights reserved.</p>
  </footer>
</body>
</html>
