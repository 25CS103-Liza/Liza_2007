<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Liza Soni — GitHub Profile</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --muted:#94a3b8;
      --accent1:#7c3aed;
      --accent2:#06b6d4;
      --glass: rgba(255,255,255,0.04);
      --radius:16px;
      color-scheme: dark;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial;background:linear-gradient(180deg,var(--bg),#071029);color:#e6eef8}
    .container{max-width:980px;margin:48px auto;padding:28px;border-radius:20px;background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);box-shadow:0 10px 30px rgba(2,6,23,0.6)}

    header{display:flex;gap:20px;align-items:center}
    .avatar{width:110px;height:110px;border-radius:22px;flex:0 0 110px;background:linear-gradient(135deg,var(--accent1),var(--accent2));display:grid;place-items:center;font-weight:800;font-size:36px;color:white}
    .intro{flex:1}
    .name{font-size:24px;font-weight:700;margin:0}
    .tagline{margin:6px 0;color:var(--muted)}

    .typing{display:inline-block;position:relative;padding-left:6px}
    .typing::after{content:"";display:inline-block;width:8px;height:18px;background:var(--accent2);margin-left:8px;border-radius:2px;animation:blink 1s steps(2) infinite}
    @keyframes blink{50%{opacity:0}}

    .chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:12px}
    .chip{background:var(--glass);padding:8px 12px;border-radius:12px;color:var(--muted);font-weight:600}

    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:26px}
    .card{background:linear-gradient(180deg,rgba(255,255,255,0.02),transparent);padding:18px;border-radius:var(--radius);box-shadow:inset 0 1px 0 rgba(255,255,255,0.02)}

    .section-title{font-weight:700;margin:0 0 8px 0}
    .stack{display:flex;flex-wrap:wrap;gap:10px}
    .stack .item{background:rgba(255,255,255,0.03);padding:8px 10px;border-radius:10px;font-weight:600;color:var(--muted)}

    .projects{display:flex;flex-direction:column;gap:12px}
    .project{padding:12px;border-radius:12px;background:linear-gradient(90deg,rgba(255,255,255,0.015),transparent);border:1px solid rgba(255,255,255,0.02)}
    .project h4{margin:0 0 6px 0}
    .project p{margin:0;color:var(--muted);font-size:14px}

    .sidebar .stats{display:grid;gap:12px}
    .socials{display:flex;gap:12px;flex-wrap:wrap}
    a.social{display:inline-flex;align-items:center;gap:8px;padding:8px 12px;border-radius:10px;background:rgba(255,255,255,0.02);text-decoration:none;color:inherit;font-weight:600}

    footer{margin-top:26px;color:var(--muted);font-size:13px;text-align:center}

    @media (max-width:900px){.grid{grid-template-columns:1fr}.avatar{width:92px;height:92px;border-radius:14px}}
  </style>
</head>
<body>
  <div class="container" id="profile">
    <header>
      <div class="avatar" id="avatar">LS</div>
      <div class="intro">
        <h1 class="name">Liza Soni</h1>
        <div class="tagline">🚀 <span class="typing">Curious mind exploring AI, Web Development & Sustainable Tech</span></div>
        <div class="chips" id="meta-chips">
          <div class="chip">📍 India</div>
          <div class="chip">💼 Computer Engineering Student</div>
          <div class="chip">🕒 Open for collaborations</div>
        </div>
      </div>
    </header>

    <div class="grid">
      <main>
        <section class="card">
          <h3 class="section-title">About</h3>
          <p style="color:var(--muted);line-height:1.6">Hi — I'm <strong>Liza Soni</strong>, a Computer Engineering student passionate about crafting intelligent and aesthetic digital experiences. I love working on projects involving <strong>AI, Image Processing, and UI/UX Design</strong>. Always eager to learn, explore, and innovate.</p>
        </section>

        <section class="card" style="margin-top:14px">
          <h3 class="section-title">Tech Stack</h3>
          <div class="stack">
            <div class="item">Python</div>
            <div class="item">C / C++</div>
            <div class="item">HTML & CSS</div>
            <div class="item">JavaScript</div>
            <div class="item">React</div>
            <div class="item">Git & GitHub</div>
            <div class="item">Machine Learning</div>
          </div>
        </section>

        <section class="card" style="margin-top:14px">
          <h3 class="section-title">Featured Projects</h3>
          <div class="projects">
            <div class="project">
              <h4>GreenHydro — Renewable Energy Dashboard</h4>
              <p>A data-driven web app promoting green hydrogen awareness and analytics.</p>
            </div>
            <div class="project">
              <h4>Baseerat — Smart Guidance System</h4>
              <p>An educational guide app using smart recommendations for career and study paths.</p>
            </div>
            <div class="project">
              <h4>Image Compression using SVD</h4>
              <p>Mathematical image compression technique implemented for efficient storage and quality balance.</p>
            </div>
          </div>
        </section>
      </main>

      <aside class="sidebar">
        <div class="card">
          <h3 class="section-title">Quick Stats</h3>
          <div class="stats">
            <img src="https://github-readme-stats.vercel.app/api?username=lizasoni&show_icons=true&theme=dark" alt="GitHub Stats" style="width:100%;border-radius:12px;" />
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lizasoni&layout=compact&theme=dark" alt="Top Languages" style="width:100%;border-radius:12px;" />
          </div>
        </div>

        <div class="card" style="margin-top:14px">
          <h3 class="section-title">Contact & Socials</h3>
          <div class="socials">
            <a class="social" href="https://github.com/lizasoni" target="_blank">GitHub</a>
            <a class="social" href="https://www.linkedin.com/in/liza-soni" target="_blank">LinkedIn</a>
            <a class="social" href="#" target="_blank">Portfolio</a>
            <a class="social" href="mailto:liza.soni@example.com">Email</a>
          </div>
        </div>

        <div class="card" style="margin-top:14px">
          <h3 class="section-title">Interests</h3>
          <p style="color:var(--muted);margin:0">Artificial Intelligence · Image Processing · UI/UX Design · Renewable Energy · Open Source</p>
        </div>
      </aside>
    </div>

    <footer>
      <small>Made with ❤️ by Liza Soni — Thanks for visiting!</small>
    </footer>
  </div>

  <script>
    (function(){
      const name = 'Liza Soni';
      const avatar = document.getElementById('avatar');
      const initials = name.split(' ').map(s=>s[0]).join('').toUpperCase();
      avatar.textContent = initials;
    })();
  </script>
</body>
</html>
