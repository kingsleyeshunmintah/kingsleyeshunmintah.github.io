<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Eshun Kingsley | Portfolio</title>

  <link rel="icon" href="https://i.ibb.co/67DbkxKz/Eshun-Kingsley-Profile-1.png">

  <meta name="description" content="Portfolio of Eshun Kingsley - Web Developer & AI Enthusiast">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }

    body {
      background: #fff;
      color: #202124;
      line-height: 1.6;
    }

    /* NAVBAR */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 40px;
      border-bottom: 1px solid #eee;
      position: sticky;
      top: 0;
      background: white;
    }

    nav h2 {
      font-size: 20px;
      font-weight: 500;
    }

    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #5f6368;
      font-size: 14px;
    }

    nav a:hover {
      color: #1a73e8;
    }

    /* HERO */
    .hero {
      text-align: center;
      padding: 80px 20px;
    }

    .hero img {
      width: 120px;
      border-radius: 50%;
      margin-bottom: 20px;
    }

    .hero h1 {
      font-size: 36px;
      font-weight: 500;
    }

    .hero p {
      color: #5f6368;
      max-width: 500px;
      margin: 15px auto;
    }

    .btn {
      padding: 10px 20px;
      margin: 10px;
      border-radius: 4px;
      text-decoration: none;
      font-size: 14px;
      display: inline-block;
    }

    .primary {
      background: #1a73e8;
      color: white;
    }

    .secondary {
      border: 1px solid #dadce0;
      color: #202124;
      background: #f8f9fa;
    }

    /* SECTIONS */
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 30px;
      font-weight: 500;
    }

    /* PROJECTS */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      border: 1px solid #eee;
      padding: 20px;
      border-radius: 8px;
      transition: 0.2s;
    }

    .card:hover {
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    .card h3 {
      margin-bottom: 10px;
    }

    .card a {
      color: #1a73e8;
      text-decoration: none;
      font-size: 14px;
    }

    /* SKILLS */
    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 10px;
    }

    .skill {
      padding: 8px 15px;
      background: #f1f3f4;
      border-radius: 20px;
      font-size: 14px;
    }

    /* CONTACT */
    .contact {
      text-align: center;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      color: #1a73e8;
      text-decoration: none;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #5f6368;
    }
  </style>
</head>

<body>

  <!-- NAVBAR -->
  <nav>
    <h2>Eshun</h2>
    <div>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <!-- HERO -->
  <div class="hero">
    <img src="https://i.ibb.co/67DbkxKz/Eshun-Kingsley-Profile-1.png">
    <h1>Eshun Kingsley</h1>
    <p>Web Developer | AI Enthusiast | Building clean and modern digital experiences.</p>

    <a href="#projects" class="btn primary">View Projects</a>
    <a href="#contact" class="btn secondary">Contact Me</a>
  </div>

  <!-- ABOUT -->
  <section id="about">
    <h2>About Me</h2>
    <p style="text-align:center; max-width:700px; margin:auto;">
      I am passionate about building web applications and AI-powered systems.
      I focus on creating simple, clean, and user-friendly experiences.
    </p>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">

      <div class="card">
        <h3>Project One</h3>
        <p>Short description of your project.</p>
        <a href="#">View on GitHub</a>
      </div>

      <div class="card">
        <h3>Project Two</h3>
        <p>Short description of your project.</p>
        <a href="#">View on GitHub</a>
      </div>

      <div class="card">
        <h3>Project Three</h3>
        <p>Short description of your project.</p>
        <a href="#">View on GitHub</a>
      </div>

    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Flutter</div>
      <div class="skill">Python</div>
      <div class="skill">AI/ML</div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Let's work together or connect.</p>
    <a href="mailto:kingsleyeshunmintah@gmail.com">Email Me</a>
    <a href="https://github.com/kingsleyeshunmintah">GitHub</a>
    <a href="https://www.linkedin.com/in/kingsley-eshun-mintah">LinkedIn</a>
    <div class="badge-base LI-profile-badge" data-locale="en_US" data-size="medium" data-theme="light" data-type="VERTICAL" data-vanity="kingsley-eshun-mintah-6519941ba" data-version="v1"><a class="badge-base__link LI-simple-link" href="https://gh.linkedin.com/in/kingsley-eshun-mintah-6519941ba?trk=profile-badge">Kingsley Eshun Mintah</a></div>
              
  </section>

  <!-- FOOTER -->
  <footer>
    © 2026 Eshun Kingsley. All rights reserved.
  </footer>
<script src="https://platform.linkedin.com/badges/js/profile.js" async defer type="text/javascript"></script>
</body>
</html>
