<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <style>
    /* General Styles */
    :root { --bg:#0f172a; --card:#111827; --text:#e5e7eb; --muted:#9ca3af; --accent:#22d3ee; }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0; font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(160deg,#0b1224 0%, #0f172a 40%, #0b1224 100%);
      color: var(--text);
    }
    a { color: inherit; text-decoration: none; }
    img { max-width: 100%; display: block; }

    /* Navbar */
    header {
      position: sticky; top: 0; z-index: 50;
      background: rgba(17,24,39,0.85); backdrop-filter: blur(8px);
      border-bottom: 1px solid rgba(255,255,255,0.06);
    }
    .nav {
      max-width: 1100px; margin: 0 auto; padding: 12px 16px;
      display: flex; align-items: center; justify-content: space-between;
    }
    .brand { font-weight: 700; letter-spacing: .5px; }
    .brand span { color: var(--accent); }
    .nav ul { list-style: none; display: flex; gap: 18px; padding: 0; margin: 0; }
    .nav a { padding: 8px 10px; border-radius: 10px; color: var(--muted); }
    .nav a:hover, .nav a:focus { color: var(--text); background: rgba(255,255,255,0.06); }

    /* Sections */
    section { padding: 70px 16px; }
    .wrap { max-width: 1100px; margin: 0 auto; }
    .hero {
      display: grid; grid-template-columns: 1.2fr 1fr; gap: 28px; align-items: center;
      padding-top: 32px;
    }
    .hero h1 { font-size: clamp(28px, 5vw, 48px); margin: 0 0 8px; }
    .hero p { color: var(--muted); margin: 0 0 20px; line-height: 1.6; }
    .cta { display: inline-flex; gap: 12px; }
    .btn {
      padding: 10px 16px; border-radius: 12px; border: 1px solid rgba(255,255,255,0.12);
      background: #0b1324; color: var(--text); cursor: pointer;
    }
    .btn.primary { background: var(--accent); color: #0b1324; border: none; font-weight: 700; }
    .btn:hover { filter: brightness(1.08); }

    /* Cards */
    .grid { display: grid; gap: 16px; }
    .grid.three { grid-template-columns: repeat(3, 1fr); }
    .grid.two { grid-template-columns: repeat(2, 1fr); }
    .card {
      background: rgba(17,24,39,0.8);
      border: 1px solid rgba(255,255,255,0.08);
      border-radius: 16px; padding: 16px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.25);
    }
    .card h3 { margin: 10px 0 6px; }
    .muted { color: var(--muted); }

    /* Contact */
    form { display: grid; gap: 12px; }
    input, textarea {
      width: 100%; padding: 12px 14px; border-radius: 12px;
      border: 1px solid rgba(255,255,255,0.14); background: #0b1324; color: var(--text);
    }
    textarea { min-height: 120px; resize: vertical; }
    .small { font-size: 12px; color: var(--muted); }

    /* Footer */
    footer { text-align: center; padding: 24px 16px; color: var(--muted); }

    /* Responsive */
    @media (max-width: 900px) {
      .hero { grid-template-columns: 1fr; }
      .grid.three { grid-template-columns: 1fr 1fr; }
    }
    @media (max-width: 600px) {
      .nav ul { gap: 8px; }
      .grid.three, .grid.two { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <header>
    <div class="nav">
      <div class="brand">Ajith<span>.Video  Editor</span></div>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
  </header>

  <!-- Hero -->
  <section id="home">
    <div class="wrap hero">
      <div>
        <h1>Hi, I’m Ajith 👋</h1>
        <p class="muted">
          B.Sc. Computer Science student.  I specialize in YouTube and Social Media content editing.  
      My editing style is fast, clean, and engaging — perfect for vlogs, reels, shorts, and brand promotions.  
      Whether it’s cinematic storytelling or trendy edits, I make videos that connect with audiences.
    </p>
     <!-- ✅ About Image -->
  <img src="F:\new audio\new file/ajith12.png" alt="Ajith Editing Profile" style="max-width:250px; border-radius:50%; margin-top:20px;">
</div>
        <div class="cta">
          <a class="btn primary" href="#projects">View Projects</a>
          <a class="btn" href="#contact">Contact Me</a>
        </div>
      </div>
      <div class="card">
        <h3>What I Do</h3>
        <p class="muted">Location: India • Focus: Davinci saftware</p>
        <ul class="muted" style="padding-left:18px; margin:10px 0 0;">
          <li>YouTube & Social Media Editing</li>
          <li>Reels, Shorts, Cinematic Cuts</li>
          <li>Fast & Engaging Transitions</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about">
    <div class="wrap grid two">
      <div>
        <h2>About Me</h2>
        <p class="muted">
           I specialize in YouTube and Social Media content editing.  
      My editing style is fast, clean, and engaging — perfect for vlogs, reels, shorts, and brand promotions.  
      Whether it’s cinematic storytelling or trendy edits, I make videos that connect with audiences.
    </p>
  </div>
        </p>
      </div>
      <div class="card">
        <h3>My Strengths</h3>
        <p class="muted">• Creative storytelling • Strong sense of timing • Trend adaptation • Consistent practice</p>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects">
    <div class="wrap">
      <h2>Projects</h2>
      <div class="grid three">
        <article class="card">
          <h3>YouTube Videos</h3>
          <p> Edited engaging YouTube videos with smooth cuts, B-roll, subtitles, and BGM sync.</p>
        <article class="card">
          <h3>Instagram Reels</h3>
          <p>Created fast-paced reels with effects, transitions, and trending music.</p>
        </article>
        <article class="card">
          <h3>YouTube Shorts</h3>
          <p>Short-form content optimized for attention, retention, and audience growth.</p>
        </article>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills">
    <div class="wrap">
      <h2>Skills</h2>
      <div class="grid three">
        <div class="card">
          <h3>Davinci saftware</h3>
          <p class="muted">I’m working Davinci saftware  in PC.</p>
        </div>
        <div class="card">
          <h3>capcut</h3>
          <p class="muted">I’m working capcut mobile phone.</p>
        </div>
        <div class="card">
          <h3>video Editor</h3>
          <p class="muted">Created fast-paced reels with effects, transitions, and trending music..</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <div class="wrap">
      <h2>Contact</h2>
      <div class="card">
        <form onsubmit="event.preventDefault(); alert('Thanks! I will reply soon.');">
          <input type="text" name="name" placeholder="Your name" required />
          <input type="email" name="email" placeholder="Your email" required />
          <textarea name="message" placeholder="Your message..." required></textarea>
          <button class="btn primary" type="submit">Send Message</button>
            <p>📧 Email: kumarajith80420@gmail.com</p>
  <p>📱 Instagram: _call_me_loosu_143</p>
  <p>▶️ YouTube: nothing its ok</p>
        </form>
      </div>
    </div>
  </section>

  <footer>
     <p>&copy; 2025 Ajith Kumar | YouTube & Social Media Video Editor | All Rights Reserved.</p>
  </footer>

  <script>
    // Set current year
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
