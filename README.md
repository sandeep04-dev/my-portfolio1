<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sandeep's Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to right, #141e30, #243b55);
      color: white;
      line-height: 1.6;
      padding: 20px;
    }
    header {
      text-align: center;
      margin-bottom: 50px;
    }
    header h1 {
      font-size: 3em;
    }
    header p {
      color: #ccc;
    }
    .section {
      margin-bottom: 50px;
    }
    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: #1e2a38;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: scale(1.05);
    }
    .contact {
      text-align: center;
    }
    .contact a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      border: 1px solid white;
      border-radius: 5px;
      text-decoration: none;
      color: white;
      transition: 0.3s;
    }
    .contact a:hover {
      background: white;
      color: #243b55;
    }
  </style>
</head>
<body>
  <header>
    <h1>Avantsa Venkata Lakshmana Sai Sandeep</h1>
    <p>Front-End Developer | HTML, CSS, JavaScript Enthusiast</p>
  </header>

  <section class="section">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card">HTML5</div>
      <div class="card">CSS3</div>
      <div class="card">JavaScript</div>
      <div class="card">Responsive Design</div>
      <div class="card">Git & GitHub</div>
    </div>
  </section>

  <section class="section">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Portfolio Website</h3>
        <p>A responsive and interactive portfolio built using HTML, CSS, and JS.</p>
      </div>
      <div class="card">
        <h3>Task Manager</h3>
        <p>A simple JavaScript-based to-do app to manage your daily tasks.</p>
      </div>
    </div>
  </section>

  <section class="section contact">
    <h2>Contact Me</h2>
    <a href="mailto:avantsasaisandeep@gmail.com">Email</a>
    <a href="https://github.com/sandeep04-dev" target="_blank">GitHub</a>
    <a href="https://linkedin.com/in/sai-sandeep-0333722b7" target="_blank">LinkedIn</a>
  </section>
</body>
</html>
