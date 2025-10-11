<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Data Science Portfolio</title>
  <style>
    html, body {
      height: 100%;
      width: 100%;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: #ffffff;
    }

    /* Navbar */
    .navbar {
      display: flex;
      justify-content: center;
      gap: 30px;
      background-color: white;
      padding: 12px 0;
      border-bottom: 2px solid #ddd;
    }
    .navbar a {
      color: #003366;
      text-decoration: none;
      font-size: 16px;
      padding: 6px 12px;
      font-weight: bold;
    }
    .navbar a:hover {
      background-color: #f0f0f0;
      border-radius: 5px;
    }

    /* Main layout */
    .content {
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      justify-items: center;
      height: calc(100vh - 60px);
      width: 100%;
      padding: 40px;
      box-sizing: border-box;
    }

    .content img {
      width: 70%;
      max-width: 400px;
      border-radius: 12px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.15);
    }

    .intro {
      max-width: 550px;
      text-align: left;
    }
    .intro h3 {
      font-size: 2em;
      color: #003366;
      margin-bottom: 10px;
    }
    .intro p {
      color: #333;
      line-height: 1.6;
      margin-bottom: 20px;
    }

    /* Social links */
    .social-links {
      display: flex;
      gap: 15px;
      flex-wrap: wrap;
      margin-top: 20px;
    }
    .social-links a img {
      border: 2px solid #000;
      border-radius: 6px;
      padding: 2px;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .social-links a img:hover {
      transform: scale(1.05);
      box-shadow: 0 0 10px rgba(0,0,0,0.15);
    }

    /* Chips */
    .chips {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 40px;
    }
    .chip {
      background-color: #e6f0ff;
      border: 1px solid #003366;
      border-radius: 25px;
      padding: 8px 16px;
      font-size: 14px;
      color: #003366;
    }

    @media (max-width: 900px) {
      .content {
        grid-template-columns: 1fr;
        text-align: center;
      }
      .intro {
        text-align: center;
      }
      .social-links {
        justify-content: center;
      }
    }
  </style>
</head>
<body>

  <nav class="navbar">
    <a href="index.html">Home</a>
    <a href="experience.html">Experience</a>
    <a href="projects.html">Projects</a>
  </nav>

  <div class="content">
    <img src="/assets/imgs/sushanth.jpg" alt="Sushanth Reddy Gangireddy">
    <div class="intro">
      <h3>Hi, I'm Sushanth!</h3>
      <p>
        I love exploring data, connecting the dots to uncover patterns, and building models that help achieve meaningful impact.
        At the heart of my work is a belief in the power of storytelling through data—seeing raw numbers weave a compelling story of their own.
      </p>
      <p>Take a look around, and feel free to reach out!</p>

      <div class="social-links">
        <a href="https://www.linkedin.com/in/sushanth-gangireddy/" target="_blank" rel="noopener noreferrer">
          <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" width="120">
        </a>
        <a href="https://github.com/sushanth128" target="_blank" rel="noopener noreferrer">
          <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" width="120">
        </a>
        <a href="https://public.tableau.com/app/profile/sushanth.reddy.gangireddy/vizzes" target="_blank" rel="noopener noreferrer">
          <img src="/assets/imgs/tableau.png" width="120" style="vertical-align: middle;">
        </a>
        <a href="mailto:sushanthreddy08@gmail.com">
          <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" width="120">
        </a>
      </div>

      <div class="chips">
        <span class="chip">Machine Learning</span>
        <span class="chip">Data Engineering</span>
        <span class="chip">Time Series Forecasting</span>
        <span class="chip">Causal Inference</span>
        <span class="chip">Visualization</span>
        <span class="chip">MLOps</span>
        <span class="chip">Python</span>
        <span class="chip">SQL</span>
      </div>
    </div>
  </div>

</body>
</html>
