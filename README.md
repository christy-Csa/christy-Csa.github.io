<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Christy Mecaller | Purple Flowers Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* General Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #a77bff, #d6b3ff);
      color: #fff;
      overflow-x: hidden;
    }

    /* Floral subtle background using overlay image */
    body::before {
      content: '';
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: url('https://i.ibb.co/PM3zJ2k/purple-flowers.png') center/cover no-repeat;
      opacity: 0.1;
      z-index: -1;
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: rgba(255,255,255,0.1);
      backdrop-filter: blur(5px);
      border-radius: 20px;
      margin: 20px;
    }

    header h1 {
      font-size: 3rem;
      color: #6a0dad; /* deep purple */
      text-shadow: 0 0 10px #d6b3ff, 0 0 20px #a77bff;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      color: #eee;
      text-shadow: 0 0 5px #fff;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 20px 0;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #d6b3ff;
      text-shadow: 0 0 10px #d6b3ff;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section h2 {
      text-align: center;
      color: #6a0dad;
      margin-bottom: 30px;
      text-shadow: 0 0 10px #a77bff;
    }

    .about, .projects, .contact {
      margin-bottom: 50px;
      background: rgba(255,255,255,0.1);
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(255,255,255,0.1);
      backdrop-filter: blur(5px);
    }

    .projects .project {
      background: rgba(255,255,255,0.15);
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(106,13,173,0.5);
    }

    .projects .project h3 {
      color: #d6b3ff;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 25px;
      background: #6a0dad;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: 0.3s;
    }

    .contact a:hover {
      background: #d6b3ff;
      color: #6a0dad;
      box-shadow: 0 0 15px #d6b3ff, 0 0 30px #6a0dad;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #eee;
      text-shadow: 0 0 5px #fff;
    }

  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Christy Mecaller</h1>
    <p>Web Developer | Designer | Tech Enthusiast</p>
  </header>

  <!-- Navigation -->
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>Hello! I'm Christy Mecaller from Palapas Pioduran. I am passionate about web development and design. I enjoy creating modern, interactive websites and bringing ideas to life with code. Constant learning and exploring new technologies keep me motivated!</p>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <h2>My Projects</h2>

    <div class="project">
      <h3>Project One</h3>
      <p>A brief description of your project goes here. Mention technologies used and what it does.</p>
    </div>

    <div class="project">
      <h3>Project Two</h3>
      <p>A brief description of your project goes here. Mention technologies used and what it does.</p>
    </div>

  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>Reach out through any platform below:</p>
    <a href="mailto:mecallerchristy9@gmail.com">Email</a>
    <a href="https://github.com/yourusername" target="_blank">GitHub</a>
    <a href="https://www.linkedin.com/in/yourprofile/" target="_blank">LinkedIn</a>
    <a href="YOUR_FACEBOOK_LINK_HERE" target="_blank">Facebook</a>
    <p>Phone: 09558577306</p>
  </section>

  <footer>
    &copy; 2026 Christy Mecaller. All rights reserved.
  </footer>

</body>
</html>
![My Image](images/profile.jpg)
