<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Liza Soni — Profile</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0e1320;
      --card: #1a2234;
      --accent1: #6d5dfc;
      --accent2: #00c3ff;
      --text: #e6edf7;
      --muted: #94a3b8;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background: linear-gradient(180deg, var(--bg), #060a15);
      color: var(--text);
      line-height: 1.6;
    }
    .container {
      max-width: 900px;
      margin: 60px auto;
      padding: 30px;
      background: rgba(255, 255, 255, 0.03);
      border-radius: 20px;
      box-shadow: 0 8px 30px rgba(0, 0, 0, 0.4);
    }
    header {
      text-align: center;
      margin-bottom: 30px;
    }
    header h1 {
      font-size: 2rem;
      background: linear-gradient(90deg, var(--accent1), var(--accent2));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin-bottom: 10px;
    }
    header p {
      color: var(--muted);
      font-size: 1rem;
    }
    section {
      background: var(--card);
      margin: 20px 0;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
    }
    h2 {
      color: var(--accent2);
      font-size: 1.2rem;
      margin-top: 0;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    li::before {
      content: "🌟";
      margin-right: 8px;
      color: var(--accent1);
    }
    .skills span {
      display: inline-block;
      background: rgba(255,255,255,0.05);
      color: var(--muted);
      padding: 8px 14px;
      border-radius: 10px;
      margin: 5px;
      font-weight: 500;
    }
    footer {
      text-align: center;
      margin-top: 30px;
      color: var(--muted);
      font-size: 0.9rem;
    }
    a {
      color: var(--accent2);
      text-decoration: none;
      font-weight: 600;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>👋 Hi, I'm Liza Soni</h1>
      <p>A Computer Science Engineering Student | Aspiring Developer</p>
    </header>

    <section>
      <h2>About Me</h2>
      <p>
        I'm a <strong>Computer Science Engineering student</strong> passionate about learning and building a strong foundation in programming. 
        As a <strong>beginner in coding</strong>, I enjoy solving small challenges and exploring new technologies that help me grow step by step.
      </p>
    </section>

    <section>
      <h2>Currently Learning</h2>
      <ul>
        <li>Programming with <strong>C</strong> and <strong>C++</strong></li>
        <li>Understanding fundamentals of logic building</li>
        <li>Exploring Data Structures and Algorithms</li>
        <li>Planning to start learning <strong>Java</strong> soon</li>
      </ul>
    </section>

    <section>
      <h2>Tech Stack</h2>
      <div class="skills">
        <span>C</span>
        <span>C++</span>
        <span>Java (soon)</span>
        <span>Git & GitHub</span>
        <span>HTML</span>
        <span>CSS</span>
      </div>
    </section>

    <section>
      <h2>Goals</h2>
      <ul>
        <li>Enhance problem-solving skills through coding practice</li>
        <li>Build real-world projects using learned technologies</li>
        <li>Contribute to open-source in the future</li>
        <li>Grow as a confident and creative software developer</li>
      </ul>
    </section>

    <section>
      <h2>Connect with Me</h2>
      <p>
        🌐 <a href="https://github.com/lizasoni" target="_blank">GitHub</a> <br>
        💼 <a href="https://www.linkedin.com/in/liza-soni" target="_blank">LinkedIn</a> <br>
        📧 <a href="mailto:liza.soni@example.com">liza.soni@example.com</a>
      </p>
    </section>

    <footer>
      <p>✨ “Every expert was once a beginner.” ✨<br>
      Made with ❤️ by Liza Soni</p>
    </footer>
  </div>
</body>
</html>
