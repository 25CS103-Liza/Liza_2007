<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GitHub Profile — README (HTML)</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724; /* dark navy */
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

    /* responsive */
    @media (max-width:900px){.grid{grid-template-columns:1fr}.avatar{width:92px;height:92px;border-radius:14px}}
  </style>
</head>
<body>
  <div class="container" id="profile">
    <header>
      <div class="avatar" id="avatar">LS</div>
      <div class="intro">
        <h1 class="name">{{Your Name}}</h1>
        <div class="tagline">🚀 <span class="typing">{{Short tagline or intro — e.g. Passionate about AI, Web Dev & Sustainable Tech}}</span></div>
        <div class="chips" id="meta-chips">
          <div class="chip">📍 {{Location or University}}</div>
          <div class="chip">💼 {{Current role or student}}</div>
          <div class="chip">🕒 Available for collaborations</div>
        </div>
      </div>
    </header>

    <div class="grid">
      <main>
        <section class="card">
          <h3 class="section-title">About</h3>
          <p id="about" style="color:var(--muted);line-height:1.6">Hi — I'm <strong>{{Your Name}}</strong>. I'm a <em>{{Current role / education}}</em> who loves building beautiful, useful things. I work at the intersection of <strong>{{Interests}}</strong>. This README is a living snapshot of my journey and projects.</p>
        </section>

        <section class="card" style="margin-top:14px">
          <h3 class="section-title">Tech Stack</h3>
          <div class="stack" id="tech-stack">
            <!-- Replace these with your techs -->
            <div class="item">Python</div>
            <div class="item">C / C++</div>
            <div class="item">HTML & CSS</div>
            <div class="item">JavaScript</div>
            <div class="item">React</div>
            <div class="item">Git</div>
            <div class="item">Machine Learning</div>
          </div>
        </section>

        <section class="card" style="margin-top:14px">
          <h3 class="section-title">Selected Projects</h3>
          <div class="projects" id="projects">
            <div class="project">
              <h4>Project One — <small>{{repo-name-1}}</small></h4>
              <p>A short one-line description of what the project does and the tech used.</p>
            </div>
            <div class="project">
              <h4>Project Two — <small>{{repo-name-2}}</small></h4>
              <p>Another highlight — quick summary, link, and impact.</p>
            </div>
            <div class="project">
              <h4>Project Three — <small>{{repo-name-3}}</small></h4>
              <p>Optional third project or an open-source contribution highlight.</p>
            </div>
          </div>
        </section>
      </main>

      <aside class="sidebar">
        <div class="card">
          <h3 class="section-title">Quick Stats</h3>
          <div class="stats">
            <!-- Badges / dynamic cards — replace USERNAME with your GitHub username -->
            <img src="https://github-readme-stats.vercel.app/api?username={{GITHUB_USERNAME}}&show_icons=true&theme=dark" alt="GitHub Stats" style="width:100%;border-radius:12px;" />
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username={{GITHUB_USERNAME}}&layout=compact&theme=dark" alt="Top Languages" style="width:100%;border-radius:12px;" />
          </div>
        </div>

        <div class="card" style="margin-top:14px">
          <h3 class="section-title">Contact & Socials</h3>
          <div class="socials">
            <a class="social" href="https://github.com/{{GITHUB_USERNAME}}" target="_blank">GitHub</a>
            <a class="social" href="https://www.linkedin.com/in/{{LINKEDIN_ID}}" target="_blank">LinkedIn</a>
            <a class="social" href="{{PORTFOLIO_URL}}" target="_blank">Portfolio</a>
            <a class="social" href="mailto:{{EMAIL}}">Email</a>
          </div>
        </div>

        <div class="card" style="margin-top:14px">
          <h3 class="section-title">Interests</h3>
          <p style="color:var(--muted);margin:0">{{Image Processing · Machine Learning · Open Source · UI/UX · Sustainable Tech}}</p>
        </div>
      </aside>
    </div>

    <footer>
      <small>Made with ❤️ — Copy this HTML into a file (README.html) or convert it to Markdown for your GitHub profile.</small>
    </footer>
  </div>

  <!-- Small script to auto-fill initials in avatar based on name placeholder -->
  <script>
    (function(){
      const nameEl = document.querySelector('.name');
      const avatar = document.getElementById('avatar');
      const name = (nameEl && nameEl.textContent.trim()) || '{{Your Name}}';
      const initials = name.split(' ').slice(0,2).map(s=>s[0]||'').join('').toUpperCase();
      avatar.textContent = initials || 'LS';
    })();
  </script>
</body>
</html>
