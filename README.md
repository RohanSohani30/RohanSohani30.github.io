<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rohan Sohani | AI/ML Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", sans-serif;
      background: #0d0d0d;
      color: #ffffff;
      scroll-behavior: smooth;
    }

    header {
      height: 100vh;
      background: linear-gradient(135deg, #1f1f1f, #000000);
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 0 10%;
    }

    h1 {
      font-size: 3.5rem;
      margin: 0;
    }

    h2 {
      font-size: 2rem;
      margin-top: 5px;
      color: #00f0ff;
    }

    .btn {
      background: #00f0ff;
      padding: 12px 24px;
      border-radius: 8px;
      text-decoration: none;
      color: #000;
      font-weight: bold;
      margin-top: 20px;
      display: inline-block;
      transition: 0.3s;
    }
    .btn:hover {
      background: #00aab3;
      transform: scale(1.05);
    }

    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(0, 0, 0, 0.7);
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      backdrop-filter: blur(10px);
    }

    nav a {
      color: #ffffff;
      margin: 0 15px;
      text-decoration: none;
      transition: 0.3s;
    }
    nav a:hover {
      color: #00f0ff;
    }

    section {
      padding: 80px 10%;
    }

    .card-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .card {
      background: #1a1a1a;
      padding: 25px;
      border-radius: 12px;
      transition: 0.3s;
      border: 1px solid #2a2a2a;
    }

    .card:hover {
      transform: translateY(-8px);
      border-color: #00f0ff;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #080808;
    }
    footer a { color: #00f0ff; text-decoration: none; }
  </style>
</head>
<body>
  <nav>
    <div><strong>Rohan Sohani</strong></div>
    <div>
      <a href="#skills">Skills</a>
      <a href="#experience">Experience</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <header>
    <h1>Hi, I'm Rohan Sohani</h1>
    <h2>Senior Data Scientist | AI/ML Engineer | LLM Specialist</h2>
    <p>Building agentic AI systems, LLM apps, RAG pipelines, and scalable machine-learning solutions.</p>
    <a href="#projects" class="btn">View My Work</a>
  </header>

  <section id="skills">
    <h2>Skills</h2>
    <div class="card-grid">
      <div class="card">Python, TensorFlow, PyTorch, SciKit-Learn</div>
      <div class="card">LLMs, Hugging Face, LangChain, RAG</div>
      <div class="card">Agentic AI, Chatbot Development</div>
      <div class="card">Computer Vision, NLP, Transformers</div>
      <div class="card">Docker, Nginx, Model Deployment</div>
      <div class="card">MySQL, MongoDB</div>
    </div>
  </section>

  <section id="experience">
    <h2>Experience</h2>
    <div class="card-grid">
      <div class="card">
        <h3>Sr. Data Scientist • Softices Consultancy</h3>
        <p>Leading AI team | LLM apps | RAG | Agentic AI | Docker deployments</p>
      </div>
      <div class="card">
        <h3>AI Developer • KGK Diamonds</h3>
        <p>Computer Vision | Data Pipelines | Real-time grading systems</p>
      </div>
      <div class="card">
        <h3>Jr. Data Scientist • Rubixe</h3>
        <p>CV + NLP Projects | Model Optimization | Business AI solutions</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="card-grid">
      <div class="card">
        <h3>Food Recognition System</h3>
        <p>0.95 IoU instance segmentation model for nutrition tracking.</p>
      </div>
      <div class="card">
        <h3>LLM Chatbot</h3>
        <p>Custom-trained domain chatbot using transformers + LangChain.</p>
      </div>
      <div class="card">
        <h3>NLP Defect Categorization</h3>
        <p>Automated router log classification with 98% accuracy.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:rohans2383@gmail.com">rohans2383@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/rohansohani30/">linkedin.com/in/rohansohani30</a></p>
    <p>GitHub: <a href="https://github.com/RohanSohani30">github.com/RohanSohani30</a></p>
  </section>

  <footer>
    © 2025 Rohan Sohani • Built with ❤️ & AI
  </footer>
</body>
</html>
