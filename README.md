

Navigation Menu
Ajith-TNSDC-FWD-DP

Code
Issues
Pull requests
Ajith-TNSDC-FWD-DP
/new.html
AJITH850
AJITH850
1 hour ago
222 lines (209 loc) · 7.87 KB

Code

Blame
Older
Newer

Add files via upload
1 hour ago
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
