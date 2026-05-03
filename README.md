<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
  <title>Sahil Arate · Full-Stack Dev & Cloud Architect</title>
  <!-- 
    This page is a pure, self-contained GitHub-style profile card with FULLY VISIBLE achievements.
    All trophy/achievement sections use modern, high-contrast visual cards.
    Icons are displayed with system-friendly emojis + clear typography and glowing accents.
    No external API required, all visible inline.
  -->
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: linear-gradient(145deg, #0b0c15 0%, #0f111a 100%);
      font-family: 'Segoe UI', 'Inter', system-ui, -apple-system, 'Fira Code', monospace;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 2rem 1rem;
    }

    /* main container similar to GitHub markdown style but richer */
    .profile-container {
      max-width: 1100px;
      width: 100%;
      margin: 0 auto;
      background: rgba(13, 17, 23, 0.65);
      backdrop-filter: blur(2px);
      border-radius: 2rem;
      padding: 1.8rem 2rem 2rem 2rem;
      box-shadow: 0 25px 45px -12px rgba(0,0,0,0.5), 0 0 0 1px rgba(59,130,246,0.15);
    }

    /* responsive adjustments */
    @media (max-width: 750px) {
      .profile-container {
        padding: 1rem;
      }
      .achievements-grid {
        gap: 0.8rem;
      }
    }

    /* Achievements section — highly visible cards */
    .achievements-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.25rem;
      margin: 2rem 0 1.5rem 0;
    }

    .achievement-card {
      background: linear-gradient(135deg, #10121f 0%, #151a2b 100%);
      border-radius: 1.5rem;
      padding: 1rem 0.8rem;
      min-width: 125px;
      flex: 1 0 120px;
      text-align: center;
      transition: transform 0.2s ease, box-shadow 0.2s;
      border: 1px solid rgba(59,130,246,0.4);
      box-shadow: 0 12px 18px -8px rgba(0,0,0,0.4);
      backdrop-filter: blur(4px);
    }

    .achievement-card:hover {
      transform: translateY(-5px);
      border-color: #3b82f6;
      box-shadow: 0 20px 28px -12px #3b82f650;
    }

    .achievement-icon {
      font-size: 3rem;
      margin-bottom: 0.5rem;
      display: inline-block;
      filter: drop-shadow(0 4px 6px #00000030);
    }

    .achievement-title {
      font-weight: 800;
      font-size: 1.05rem;
      background: linear-gradient(120deg, #c084fc, #60a5fa);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
      letter-spacing: -0.2px;
    }

    .achievement-desc {
      font-size: 0.7rem;
      font-family: monospace;
      color: #94a3b8;
      margin-top: 6px;
      font-weight: 500;
    }

    /* special glow for highlight cards — extra visibility */
    .glow-accent {
      border-image: none;
      box-shadow: 0 0 0 1px #3b82f660, 0 10px 20px -5px #00000055;
    }

    /* rest of the components (stats, tech stacks etc) */
    .stats-wrap {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
      margin: 2rem 0;
    }

    .stat-card {
      background: #0f1222dd;
      border-radius: 1.2rem;
      overflow: hidden;
      box-shadow: 0 8px 18px rgba(0,0,0,0.3);
      border: 1px solid #2d3a5e;
    }

    .section-title {
      font-size: 1.8rem;
      font-weight: 700;
      background: linear-gradient(95deg, #e2e8f0, #a5b4fc);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
      margin: 1rem 0 0.8rem 0;
      border-left: 4px solid #3b82f6;
      padding-left: 1rem;
    }

    .tech-badge {
      display: inline-flex;
      background: #1e293b;
      padding: 0.25rem 0.8rem;
      border-radius: 30px;
      font-size: 0.75rem;
      font-weight: 500;
      margin: 0.2rem;
      color: #cbd5e6;
      transition: all 0.1s;
    }
    .tech-badge:hover {
      background: #2d3b5a;
      color: white;
    }

    hr {
      border: 0;
      height: 1px;
      background: linear-gradient(90deg, #3b82f680, #a855f780, #3b82f680);
      margin: 1rem 0;
    }

    .inline-code {
      background: #0a0c15;
      font-family: 'Fira Code', monospace;
      padding: 0.2rem 0.4rem;
      border-radius: 8px;
      color: #7dd3fc;
      font-size: 0.8rem;
    }

    /* footer wave and extras */
    .wave-svg {
      margin-top: 1.5rem;
    }
  </style>
</head>
<body>
<div class="profile-container">
  
  <!-- === HEADER (same as original but with crisp text) === -->
  <div align="center">
    <svg width="100%" height="200" viewBox="0 0 860 200" xmlns="http://www.w3.org/2000/svg" style="max-width:860px">
      <defs>
        <linearGradient id="hbg" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%"   stop-color="#0f0c29"/>
          <stop offset="50%"  stop-color="#302b63"/>
          <stop offset="100%" stop-color="#24243e"/>
        </linearGradient>
        <linearGradient id="hline" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%"   stop-color="#3B82F6"/>
          <stop offset="100%" stop-color="#8B5CF6"/>
        </linearGradient>
      </defs>
      <rect width="860" height="200" rx="16" fill="url(#hbg)"/>
      <rect y="0"   width="860" height="4" rx="2" fill="url(#hline)"/>
      <rect y="196" width="860" height="4" rx="2" fill="url(#hline)"/>
      <circle cx="790" cy="45"  r="60" fill="#3B82F6" fill-opacity="0.07"/>
      <circle cx="70"  cy="155" r="50" fill="#8B5CF6" fill-opacity="0.07"/>
      <text x="430" y="80" text-anchor="middle" font-family="'Segoe UI',Arial,sans-serif" font-size="46" font-weight="700" fill="#FFFFFF" letter-spacing="2">Sahil Arate</text>
      <text x="430" y="118" text-anchor="middle" font-family="'Segoe UI',Arial,sans-serif" font-size="16" fill="#94A3B8">Full-Stack Developer  •  Cloud &amp; DevOps Enthusiast  •  Java + TypeScript</text>
      <text x="430" y="155" text-anchor="middle" font-family="'Courier New',monospace" font-size="13" fill="#3B82F6">{ building scalable systems · exploring AI · open to opportunities }</text>
    </svg>
    <br/>
    <!-- coder animation (GitHub CDN) -->
    <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="550" alt="coder animation" style="max-width:100%; border-radius:20px; margin-top:5px;"/>
  </div>

  <br/>
  <div align="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2500&pause=800&color=3B82F6&center=true&vCenter=true&width=620&lines=Java+%2B+TypeScript+Full-Stack+Developer+%E2%98%95;Building+Scalable+Cloud-Native+Systems+%E2%98%81%EF%B8%8F;Kafka+%7C+Docker+%7C+AWS+%7C+Microservices+%F0%9F%9A%80;Exploring+AI+%26+LLM+Integration+%F0%9F%A4%96;Open+to+Exciting+SDE+Opportunities+%F0%9F%91%8B" alt="Typing SVG"/>
  </div>

  <div align="center" style="margin: 1rem 0;">
    <a href="https://www.linkedin.com/in/sahil-arate-ba9a14254/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
    <a href="https://sahil-portfolio-orpin.vercel.app"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=vercel&logoColor=white"/></a>
    <a href="https://www.instagram.com/arate_sahil/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
    <img src="https://komarev.com/ghpvc/?username=SahilArate&label=Profile+Views&color=3B82F6&style=for-the-badge"/>
  </div>

  <hr/>

  <!-- About Me + code block -->
  <div style="display: flex; flex-wrap: wrap; gap: 1rem; justify-content: space-between;">
    <div style="flex:2; min-width: 240px;">
      <h2 class="section-title">🧑‍💻 About Me</h2>
      <pre style="background:#0d1117; padding: 1.2rem; border-radius: 1rem; border-left: 5px solid #3b82f6; font-family: 'Fira Code', monospace; font-size: 0.8rem; color:#c9d1d9; overflow-x: auto;">
const sahil = {
  name:      "Sahil Arate",
  role:      "Full-Stack Developer",
  location:  "India 🇮🇳",
  languages: ["Java", "TypeScript", "JavaScript", "Go", "C", "SQL"],
  frontend:  ["React", "Next.js", "Tailwind CSS"],
  backend:   ["Node.js", "Express", "Go", "Spring Boot"],
  databases: ["MongoDB", "MySQL", "SQLite"],
  devOps:    ["Docker", "AWS", "Linux", "Kafka", "Git"],
  funFact:   "I debug with console.log() — no shame! 😄"
};</pre>
    </div>
    <div style="flex:1; min-width: 200px;">
      <img alt="Coding illustration" width="100%" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" style="border-radius: 20px; max-width: 280px;"/>
    </div>
  </div>

  <!-- ============================================================= -->
  <!-- 🏆 ACHIEVEMENTS SECTION — FULLY VISIBLE, PROMINENT CARDS       -->
  <!-- ============================================================= -->
  <div style="margin: 2rem 0 0.5rem 0;">
    <h2 class="section-title" style="margin-bottom: 1rem;">🏆 Achievements & Milestones</h2>
    <div class="achievements-grid">
      <!-- Trophy 1: Multi-Language Expert -->
      <div class="achievement-card">
        <div class="achievement-icon">🏆</div>
        <div class="achievement-title">Multi-Language</div>
        <div class="achievement-desc">Java · Go · TypeScript</div>
        <div class="achievement-desc" style="color:#a5f3fc;">full‑stack polyglot</div>
      </div>
      <!-- Trophy 2: 100+ Commits Streak -->
      <div class="achievement-card">
        <div class="achievement-icon">⭐</div>
        <div class="achievement-title">Consistent Commits</div>
        <div class="achievement-desc">200+ contributions</div>
        <div class="achievement-desc" style="color:#a5f3fc;">active 2024–2025</div>
      </div>
      <!-- Trophy 3: Daily Builder / Streak Master -->
      <div class="achievement-card">
        <div class="achievement-icon">🔥</div>
        <div class="achievement-title">Streak Builder</div>
        <div class="achievement-desc">daily coding rhythm</div>
        <div class="achievement-desc" style="color:#a5f3fc;">open source mindset</div>
      </div>
      <!-- Trophy 4: Problem Solver / DSA -->
      <div class="achievement-card">
        <div class="achievement-icon">💡</div>
        <div class="achievement-title">Problem Solver</div>
        <div class="achievement-desc">DSA · System Design</div>
        <div class="achievement-desc" style="color:#a5f3fc;">optimization focus</div>
      </div>
      <!-- Trophy 5: Open Source Contributor -->
      <div class="achievement-card">
        <div class="achievement-icon">🚀</div>
        <div class="achievement-title">Open Source</div>
        <div class="achievement-desc">community contributions</div>
        <div class="achievement-desc" style="color:#a5f3fc;">collaborative dev</div>
      </div>
      <!-- Trophy 6: Cloud & DevOps Builder -->
      <div class="achievement-card">
        <div class="achievement-icon">☁️</div>
        <div class="achievement-title">Cloud Builder</div>
        <div class="achievement-desc">AWS · Docker · Kafka</div>
        <div class="achievement-desc" style="color:#a5f3fc;">microservices ready</div>
      </div>
      <!-- Extra special card: AI Explorer achievement (visible and distinct) -->
      <div class="achievement-card" style="border-color:#c084fc;">
        <div class="achievement-icon">🤖</div>
        <div class="achievement-title" style="background: linear-gradient(120deg,#f472b6,#a78bfa); background-clip:text; -webkit-background-clip:text;">AI Explorer</div>
        <div class="achievement-desc">LangChain · RAG · LLMs</div>
        <div class="achievement-desc" style="color:#c4b5fd;">next‑gen integration</div>
      </div>
    </div>
  </div>

  <!-- additional achievement highlight text (visible proof) -->
  <div align="center" style="background:#11182780; border-radius: 2rem; padding: 0.7rem; margin: 0.5rem 0 1rem 0; backdrop-filter: blur(4px);">
    <span style="font-family: monospace; color: #e2e8f0;">✨ <strong style="color:#38bdf8;">6+ core achievements</strong> — multi-language expert · cloud architect · consistent open-source contributor ✨</span>
  </div>

  <!-- GitHub Stats + Activity Graph (fully visible, no removal) -->
  <h2 class="section-title">📊 GitHub Analytics</h2>
  <div class="stats-wrap">
    <div class="stat-card">
      <img src="https://github-readme-stats.vercel.app/api?username=SahilArate&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&rank_icon=github&include_all_commits=true" width="100%" alt="GitHub Stats"/>
    </div>
    <div class="stat-card">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SahilArate&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" width="100%" alt="Top Languages"/>
    </div>
  </div>
  <div align="center" style="margin-bottom: 1rem;">
    <img src="https://streak-stats.demolab.com?user=SahilArate&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="GitHub Streak"/>
  </div>
  <div align="center">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=SahilArate&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="contribution graph"/>
  </div>

  <!-- Tech Stack table (original style + enhanced visibility) -->
  <h2 class="section-title">🛠️ Tech Stack</h2>
  <div style="background: #0e1120cc; border-radius: 1.5rem; padding: 1rem;">
    <table style="width:100%; border-collapse: separate; border-spacing: 0 8px;">
      <tr><td style="width:100px;"><b>Languages</b></td><td><span class="tech-badge">Java</span> <span class="tech-badge">TypeScript</span> <span class="tech-badge">JavaScript</span> <span class="tech-badge">Go</span> <span class="tech-badge">C</span> <span class="tech-badge">SQL</span></td></tr>
      <tr><td><b>Frontend</b></td><td><span class="tech-badge">React</span> <span class="tech-badge">Next.js</span> <span class="tech-badge">Tailwind CSS</span> <span class="tech-badge">HTML5/CSS3</span></td></tr>
      <tr><td><b>Backend</b></td><td><span class="tech-badge">Node.js</span> <span class="tech-badge">Express</span> <span class="tech-badge">Spring Boot</span> <span class="tech-badge">Go</span> <span class="tech-badge">Kafka</span></td></tr>
      <tr><td><b>Databases</b></td><td><span class="tech-badge">MongoDB</span> <span class="tech-badge">MySQL</span> <span class="tech-badge">SQLite</span></td></tr>
      <tr><td><b>DevOps & Cloud</b></td><td><span class="tech-badge">Docker</span> <span class="tech-badge">AWS</span> <span class="tech-badge">Linux</span> <span class="tech-badge">GitHub Actions</span> <span class="tech-badge">Git</span></td></tr>
      <tr><td><b>Tools</b></td><td><span class="tech-badge">Figma</span> <span class="tech-badge">Arduino</span> <span class="tech-badge">Postman</span></td></tr>
    </table>
  </div>

  <!-- Learning + Quote -->
  <div style="display: flex; flex-wrap: wrap; gap: 1.5rem; margin: 2rem 0 1rem;">
    <div style="flex:1; background:#01091466; border-radius: 1.2rem; padding: 1rem;">
      <h3 style="color:#e2e8f0;">🌱 Currently Learning</h3>
      <ul style="color:#b9c7d9; margin-top: 0.6rem; list-style-type: none;">
        <li>🤖 <strong>AI Integration</strong> – LangChain, RAG pipelines, Gemini/OpenAI APIs</li>
        <li>☁️ <strong>Cloud Architecture</strong> – AWS serverless, microservices patterns</li>
        <li>🏗️ <strong>System Design</strong> – Distributed systems, scalability</li>
        <li>⚡ <strong>Backend Performance</strong> – Go concurrency, Kafka streaming</li>
        <li>🔧 <strong>DevOps</strong> – CI/CD, Kubernetes fundamentals</li>
      </ul>
    </div>
    <div style="flex:1; background:#01091466; border-radius: 1.2rem; padding: 1rem; text-align: center;">
      <h3 style="color:#e2e8f0;">💭 Dev Quote of the Day</h3>
      <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" width="100%" alt="quote"/>
    </div>
  </div>

  <!-- Connect & Call to action -->
  <hr />
  <div align="center">
    <h3 style="color:#cbd5e6;">📫 Let's Connect & Build Together</h3>
    <p style="color:#94a3b8; max-width: 600px; margin: 0.5rem auto;">I'm actively looking for <strong class="inline-code">SDE / Full-Stack / Backend</strong> roles. Open to exciting collaborations & innovative projects. Let's create impact 🚀</p>
    <div style="margin: 1rem 0;">
      <a href="https://www.linkedin.com/in/sahil-arate-ba9a14254/"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>&nbsp;&nbsp;
      <a href="https://sahil-portfolio-orpin.vercel.app"><img src="https://img.shields.io/badge/View%20Portfolio-FF5722?style=for-the-badge&logo=vercel&logoColor=white"/></a>
    </div>
  </div>

  <!-- footer wave SVG inline & star message -->
  <div align="center" class="wave-svg">
    <svg width="100%" height="70" viewBox="0 0 860 70" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
      <defs>
        <linearGradient id="wvGrad" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#06B6D4"/>
          <stop offset="50%" stop-color="#8B5CF6"/>
          <stop offset="100%" stop-color="#3B82F6"/>
        </linearGradient>
      </defs>
      <path d="M0,30 C150,55 300,10 450,30 C600,55 750,10 860,30 L860,70 L0,70 Z" fill="url(#wvGrad)" fill-opacity="0.85"/>
      <path d="M0,48 C150,30 300,65 450,48 C600,30 750,65 860,48 L860,70 L0,70 Z" fill="url(#wvGrad)" fill-opacity="0.4"/>
    </svg>
  </div>
  <div align="center" style="margin-top: 0.8rem;">
    <sub>⭐ <b>If you like what you see, drop a star on a repo — it keeps me building!</b> ⭐</sub>
    <br/>
    <sub style="color:#6c7a91;">✨ Achievements fully visible — every trophy represents real skills ✨</sub>
  </div>
</div>
</body>
</html>
