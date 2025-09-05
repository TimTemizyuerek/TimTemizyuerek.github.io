<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    /* General styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f4f4f9;
      color: #333;
    }

    /* Navbar */
    nav {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background: #4a90e2;
      color: white;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      z-index: 1000;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }

    /* Sections */
    section {
      padding: 5rem 2rem;
      min-height: 100vh;
    }
    #home {
      background: #4a90e2;
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    #home h1 {
      font-size: 2.5rem;
    }
    #about, #projects, #contact {
      background: white;
      margin: 2rem auto;
      border-radius: 10px;
      max-width: 800px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 2rem;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 1rem;
      background: #222;
      color: #ccc;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <h1>Hi, I'm [Your Name]</h1>
    <p>Welcome to my portfolio website 🚀</p>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I'm a developer/designer/student/etc. This is where you can introduce
      yourself in a few sentences. GitHub Pages makes it easy to share my work!
    </p>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>Project 1:</strong> A cool app I built.</li>
      <li><strong>Project 2:</strong> Another interesting project.</li>
      <li><strong>Project 3:</strong> Something fun to share.</li>
    </ul>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Me</h2>
    <p>
      You can find me on <a href="https://github.com/your-username" target="_blank">GitHub</a>.
    </p>
    <p>Email: <a href="mailto:you@example.com">you@example.com</a></p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 My Portfolio</p>
  </footer>
</body>
</html>
