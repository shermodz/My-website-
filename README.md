# My-website-<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Shermodz — Science as a Way to See the World</title>
  <meta name="description" content="Shermodz: a community for sharing scientific knowledge and building out-of-the-box thinking across physics, engineering, chemistry, materials and more." />
  <meta name="theme-color" content="#0b3b66" />
  <style>
    :root{
      --bg:#f6fbff; --card:#ffffff; --accent:#0b3b66; --muted:#556677;
      --accent-2:#00a3cc; --glass: rgba(255,255,255,0.7);
      --radius:12px; font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#f0fbff 0%,var(--bg) 100%);color:#112;line-height:1.5}
    .wrap{max-width:1100px;margin:32px auto;padding:20px}
    header{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:20px}
    nav a{margin-left:14px;color:var(--accent);text-decoration:none;font-weight:600}
    .hero{display:grid;grid-template-columns:1fr 360px;gap:28px;margin-top:28px;align-items:center}
    .hero .card{background:var(--card);padding:26px;border-radius:var(--radius);box-shadow:0 6px 24px rgba(10,20,40,0.06)}
    h1{margin:0 0 8px 0;font-size:28px;color:var(--accent)}
    p.lead{margin:0;color:var(--muted)}
    .cta{margin-top:16px;display:flex;gap:12px}
    .btn{padding:10px 16px;border-radius:12px;border:0;cursor:pointer;font-weight:700}
    .btn-primary{background:var(--accent);color:#fff}
    .btn-ghost{background:transparent;color:var(--accent);border:2px solid rgba(11,59,102,0.08)}
    .topics{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin-top:22px}
    .topic{background:linear-gradient(180deg,#fff, #fbfeff);padding:16px;border-radius:10px;border:1px solid rgba(10,20,40,0.04)}
    .resources{display:grid;grid-template-columns:1fr 320px;gap:18px;margin-top:28px}
    .card.small{padding:14px}
    .links a{display:block;color:var(--accent);text-decoration:none;margin-bottom:8px;font-weight:600}
    footer{margin-top:36px;padding:18px 12px;border-radius:10px;background:var(--card);display:flex;justify-content:space-between;align-items:center;box-shadow:0 6px 12px rgba(10,20,40,0.04)}
    .tagline{color:var(--muted)}
    @media (max-width:880px){.hero{grid-template-columns:1fr}.resources{grid-template-columns:1fr}.wrap{margin:12px}}
    .quote{font-style:italic;color:var(--muted);margin-top:12px}
    .topics .topic h4{margin:0 0 6px 0;color:var(--accent)}
    .subscribe{display:flex;gap:8px;margin-top:12px}
    input[type="email"]{padding:10px;border-radius:10px;border:1px solid #d6e7f3;flex:1}
    .smallprint{font-size:13px;color:#7a8b9b;margin-top:8px}
    .socials a{margin-right:10px;color:var(--accent);text-decoration:none;font-weight:600}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo">S</div>
        <div>
          <div style="font-weight:800;color:var(--accent)">Shermodz</div>
          <div style="font-size:13px;color:var(--muted)">Science is not a subject, it is a way to see the world</div>
        </div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#topics">Topics</a>
        <a href="#resources">Resources</a>
        <a href="#join">Join</a>
      </nav>
    </header>

    <section class="hero">
      <div class="card">
        <h1>Build an out-of-the-box scientific mindset</h1>
        <p class="lead">Shermodz is a community for sharing incredible scientific knowledge and turning fictional ideas into practical reality across physics, engineering, materials and more.</p>
        <div class="cta">
          <a class="btn btn-primary" href="#join">Join Community</a>
          <a class="btn btn-ghost" href="#resources">Explore Research</a>
        </div>
        <div class="quote">"Science is not a subject, it is a way to see the world"</div>

        <div id="about" style="margin-top:18px">
          <h3 style="margin-bottom:6px;color:var(--accent)">Mission</h3>
          <p class="smallprint">Share new technologies discovered by Shermodz, teach scientific thinking, help solve real-life problems with evidence-based approaches and guide contributors from imagination to working prototypes.</p>
        </div>
      </div>

      <aside>
        <div class="card small">
          <h4 style="margin:0 0 8px 0;color:var(--accent)">Quick Links</h4>
          <div class="links">
            <a href="https://shermodz.blogspot.com" target="_blank" rel="noopener">Blog — shermodz.blogspot.com</a>
            <a href="https://whatsapp.com/channel/0029VbB594THgZWaplNfWj2L" target="_blank" rel="noopener">WhatsApp Channel</a>
            <a href="https://aratt.ai/@shermodz" target="_blank" rel="noopener">Arattai Channel</a>
            <a href="https://orcid.org/0009-0000-4201-8418" target="_blank" rel="noopener">ORCID — Shermodz</a>
            <a href="https://youtube.com/@shermodz" target="_blank" rel="noopener">YouTube Channel</a>
          </div>
        </div>

        <div class="card small" style="margin-top:12px">
          <h4 style="margin:0 0 8px 0;color:var(--accent)">Subscribe</h4>
          <p class="smallprint">Get updates about new research, projects and calls for contributors.</p>
          <div class="subscribe">
            <input type="email" placeholder="Your email" id="email">
            <button class="btn btn-primary" onclick="subscribe()">Subscribe</button>
          </div>
          <div class="smallprint" id="submsg"></div>
        </div>
      </aside>
    </section>

    <section id="topics" style="margin-top:26px">
      <h3 style="color:var(--accent);margin-bottom:12px">Topics We Cover</h3>
      <div class="topics">
        <div class="topic">
          <h4>Classical Physics</h4>
          <div class="smallprint">Mechanics, waves, thermodynamics, problem-solving labs.</div>
        </div>
        <div class="topic">
          <h4>Theoretical Physics</h4>
          <div class="smallprint">Models, mathematical methods, research notes and idea incubation.</div>
        </div>
        <div class="topic">
          <h4>Quantum Mechanics & Relativity</h4>
          <div class="smallprint">Concept explanations, experiments, translation of theory to tech.</div>
        </div>
        <div class="topic">
          <h4>Engineering & Electronics</h4>
          <div class="smallprint">Prototyping guides, circuit examples, systems thinking.</div>
        </div>
        <div class="topic">
          <h4>Inorganic Chemistry & Materials</h4>
          <div class="smallprint">Material design, synthesis concepts, characterization basics.</div>
        </div>
        <div class="topic">
          <h4>Psychology & Problem Solving</h4>
          <div class="smallprint">Creativity exercises, cognitive techniques for scientific thinking.</div>
        </div>
      </div>
    </section>

    <section id="resources" class="resources">
      <div class="card">
        <h3 style="color:var(--accent)">Featured Resources</h3>
        <ul style="padding-left:18px">
          <li><strong>Intro to Shermodz</strong> — Short video and manifesto on our YouTube channel.</li>
          <li><strong>Open Research</strong> — Contribute and track research using our ORCID profile.</li>
          <li><strong>Community Labs</strong> — Step-by-step projects to build small prototypes at home.</li>
          <li><strong>Idea to Reality</strong> — Framework posts that translate fictional tech into engineering sketches.</li>
        </ul>

        <h4 style="margin-top:14px;color:var(--accent)">How to Contribute</h4>
        <ol style="padding-left:18px">
          <li>Share a short idea or paper on the blog.</li>
          <li>Join discussions on WhatsApp or Arattai.</li>
          <li>Upload your experimental data or schematics for peer feedback.</li>
        </ol>
      </div>

      <aside class="card small">
        <h4 style="color:var(--accent)">Community</h4>
        <p class="smallprint">Join channels, watch project videos, follow updates and collaborate on open problems.</p>
        <div style="margin-top:10px" class="socials">
          <a href="https://youtube.com/@shermodz" target="_blank" rel="noopener">YouTube</a>
          <a href="https://shermodz.blogspot.com" target="_blank" rel="noopener">Blog</a>
          <a href="https://whatsapp.com/channel/0029VbB594THgZWaplNfWj2L" target="_blank" rel="noopener">WhatsApp</a>
        </div>

        <h4 style="margin-top:14px;color:var(--accent)">ORCID</h4>
        <p class="smallprint"><a href="https://orcid.org/0009-0000-4201-8418" target="_blank" rel="noopener">https://orcid.org/0009-0000-4201-8418</a></p>
      </aside>
    </section>

    <section id="join" style="margin-top:26px">
      <div class="card">
        <h3 style="color:var(--accent)">Get Involved</h3>
        <p class="smallprint">Contributors are welcome. Whether you have a research note, a prototype, or a curious question — Shermodz is a place to share, test and scale ideas.</p>

        <h4 style="margin-top:10px;color:var(--accent)">Contact & Submissions</h4>
        <p class="smallprint">Send submissions or questions to: <a href="mailto:shermodz@example.com">shermodz@example.com</a>. For quick chat, join our WhatsApp channel linked above.</p>

        <div style="margin-top:12px">
          <label style="display:block;color:var(--muted);font-weight:600;margin-bottom:6px">Share a short idea</label>
          <textarea id="idea" rows="4" style="width:100%;padding:12px;border-radius:10px;border:1px solid #e6f0f8"></textarea>
          <div style="margin-top:8px">
            <button class="btn btn-primary" onclick="submitIdea()">Submit Idea</button>
          </div>
          <div id="ideamsg" class="smallprint"></div>
        </div>
      </div>
    </section>

    <footer>
      <div>
        <div style="font-weight:800;color:var(--accent)">Shermodz</div>
        <div class="tagline">Science is not a subject, it is a way to see the world</div>
      </div>
      <div style="text-align:right">
        <div style="font-size:13px;color:var(--muted)">Links</div>
        <div style="margin-top:6px"><a href="https://shermodz.blogspot.com" target="_blank" rel="noopener">Blog</a> · <a href="https://youtube.com/@shermodz" target="_blank" rel="noopener">YouTube</a></div>
      </div>
    </footer>
  </div>

  <script>
    function subscribe(){
      const email = document.getElementById('email').value.trim();
      const msg = document.getElementById('submsg');
      if(!email || !email.includes('@')){ msg.textContent = 'Please enter a valid email.'; msg.style.color='crimson'; return; }
      msg.textContent = 'Thanks! We will send updates to ' + email + '.';
      msg.style.color='green';
    }
    function submitIdea(){
      const idea = document.getElementById('idea').value.trim();
      const msg = document.getElementById('ideamsg');
      if(!idea){ msg.textContent = 'Please write a short description of your idea.'; msg.style.color='crimson'; return; }
      // Replace this with real submission code when you connect a backend or email
      msg.textContent = 'Idea received. Thank you for contributing. Please also email a detailed version to shermodz@example.com';
      msg.style.color='green';
      document.getElementById('idea').value='';
    }
  </script>
</body>
</html>
