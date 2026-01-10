<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Christy Mecaller | Purple Flower Portfolio</title>
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
      background: radial-gradient(circle at top, #2b003f 0%, #120018 100%);
      color: #fff;
      overflow-x: hidden;
    }

    /* Flower background */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background: url('https://i.ibb.co/zF9ZC2H/purple-flower-bg.png') repeat;
      opacity: 0.25;
      z-index: -1;
      animation: floatBg 120s linear infinite;
    }

    @keyframes floatBg {
      from { background-position: 0 0; }
      to { background-position: 4000px 2000px; }
    }

    header {
      text-align: center;
      padding: 90px 20px;
      background: rgba(0,0,0,0.55);
      backdrop-filter: blur(6px);
    }

    .profile-img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #c77dff;
      box-shadow: 0 0 25px #c77dff;
      margin-bottom: 20px;
    }

    header h1 {
      font-size: 3rem;
      color: #e0aaff;
      text-shadow: 0 0 12px #c77dff;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1rem;
      color: #ddd;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 25px;
      padding: 20px 0;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #e0aaff;
      text-shadow: 0 0 10px #c77dff;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section h2 {
      text-align: center;
      color: #c77dff;
      margin-bottom: 30px;
      text-shadow: 0 0 10px #c77dff;
    }

    .about, .projects, .contact {
      background: rgba(255,255,255,0.06);
      padding: 30px;
      border-radius: 18px;
      box-shadow: 0 0 20px rgba(199,125,255,0.25);
      backdrop-filter: blur(6px);
      margin-bottom: 50px;
    }

    .info {
      text-align: center;
      margin-top: 15px;
      color: #f1e6ff;
      line-height: 1.8;
    }

    .projects .project {
      background: rgba(255,255,255,0.1);
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 12px;
      box-shadow: 0 0 12px rgba(199,125,255,0.6);
    }

    .projects h3 {
      color: #e0aaff;
      margin-bottom: 8px;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 12px 26px;
      background: #c77dff;
      color: #fff;
      text-decoration: none;
      border-radius: 25px;
      font-weight: bold;
      transition: 0.3s;
    }

    .contact a:hover {
      background: #e0aaff;
      box-shadow: 0 0 18px #e0aaff;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #ccc;
      font-size: 0.9rem;
    }
  </style>
</head>

<body>

  <!-- Header -->
  <header>
    <img src="IMG_1746250030080" alt="Profile Photo" class="profile-img">
    <h1>Christy Mecaller</h1>
    <p>Student | Aspiring Web Developer</p>
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
    <p>
      Hello! I’m <strong>Christy Mecaller</strong>, a student passionate about web development and creative design.
      I love working with HTML, CSS, and JavaScript to create beautiful and functional websites inspired by nature and creativity.
    </p>

    <div class="info">
      📍 <strong>Address:</strong> Palapas, Pioduran, Albay <br>
      📞 <strong>Contact:</strong> 0955 857 7306
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <h2>My Projects</h2>

    <div class="project">
      <h3>Student Portfolio Website</h3>
      <p>A personal portfolio showcasing my skills, profile, and school projects using HTML and CSS.</p>
    </div>

    <div class="project">
      <h3>Simple Web Page Design</h3>
      <p>A beginner-friendly project focused on layout, colors, and responsive design.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>You can reach me through:</p>
    <a href="mailto:mecallerchristy9@gmail.com">Email</a>
    <a href="https://github.com/yourusername" target="_blank">GitHub</a>
    <a href="YOUR_FACEBOOK_LINK_HERE" target="_blank">Facebook</a>
  </section>

  <footer>
    &copy; 2026 Christy Mecaller. All rights reserved.
  </footer>

</body>
</html>
