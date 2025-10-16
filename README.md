
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>SHERMODZ — Science, Imagination, Invention</title>
<meta name="description" content="SHERMODZ — community for sharing scientific knowledge, building out-of-the-box thinking, experiments, quizzes and live interactive lessons."/>
<style>
  :root{
    --bg:#0b0f1a;
    --panel:#0f1724;
    --muted:#9aa7c7;
    --accent1:#6ee7ff;
    --accent2:#a78bfa;
    --glass: rgba(255,255,255,0.03);
    --glass-2: rgba(255,255,255,0.02);
    --card: linear-gradient(135deg, rgba(68,35,197,0.12), rgba(14,165,233,0.06));
    --radius:14px;
    font-family: Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
  }
  *{box-sizing:border-box}
  html,body{height:100%}
  body{
    margin:0;
    background:
      radial-gradient(800px 400px at 10% 10%, rgba(106,90,255,0.08), transparent 6%),
      radial-gradient(700px 350px at 90% 90%, rgba(34,211,238,0.06), transparent 6%),
      var(--bg);
    color:#e6eef8;
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale;
    line-height:1.45;
  }

  header{
    position:sticky; top:12px; z-index:30;
    max-width:1100px; margin:18px auto; padding:12px; display:flex; gap:14px;
    align-items:center; background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.00));
    border-radius:12px; backdrop-filter: blur(6px);
    box-shadow: 0 6px 30px rgba(2,6,23,0.6);
    border:1px solid rgba(255,255,255,0.03);
  }
  .brand{display:flex; gap:12px; align-items:center;}
  .logo{
    width:64px; height:64px; padding:8px; background:var(--glass); border-radius:12px; display:flex; align-items:center; justify-content:center;
    border:1px solid rgba(255,255,255,0.04);
  }
  .logo svg{width:44px;height:44px}
  h1{font-size:20px;margin:0;letter-spacing:0.6px}
  .tagline{font-size:12px;color:var(--muted); margin-top:2px}
  nav{margin-left:auto; display:flex; gap:10px; align-items:center}
  nav a{color:var(--accent1); text-decoration:none; font-weight:600; font-size:13px; padding:8px 12px; border-radius:8px}
  nav a:hover{background:rgba(110,231,255,0.06)}

  main{max-width:1100px;margin:28px auto;padding:20px}
  .hero{
    display:grid; grid-template-columns:1fr 420px; gap:22px; align-items:center;
    background: linear-gradient(135deg, rgba(10,12,30,0.7), rgba(6,8,20,0.85));
    padding:26px; border-radius:18px; border:1px solid rgba(255,255,255,0.03);
  }
  .hero h2{margin:0;font-size:28px;color: #eef6ff}
  .hero p{color:var(--muted); margin-top:10px}
  .motto{margin-top:14px; font-weight:600; color:var(--accent2)}
  .actions{display:flex; gap:10px; margin-top:18px}
  .btn{
    background:linear-gradient(90deg,var(--accent1),var(--accent2));
    color:#021025; padding:10px 14px; border-radius:12px; font-weight:700; text-decoration:none; font-size:13px;
    box-shadow:0 8px 30px rgba(99,102,241,0.12);
  }
  .outline{border:1px solid rgba(255,255,255,0.06); padding:10px 14px; border-radius:12px; color:var(--muted); background:transparent; text-decoration:none; font-weight:600}
  .links small{display:block;color:var(--muted); margin-top:8px}

  .card{
    background: linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.00));
    padding:16px; border-radius:14px; border:1px solid rgba(255,255,255,0.03);
  }

  /* Subjects grid */
  .grid{display:grid; grid-template-columns:repeat(3,1fr); gap:14px; margin-top:22px}
  @media(max-width:980px){ .hero{grid-template-columns:1fr} .grid{grid-template-columns:repeat(2,1fr)} nav{display:none} }
  @media(max-width:640px){ .grid{grid-template-columns:1fr} header{padding:12px; margin:8px} }

  .subject{
    padding:14px; border-radius:12px; background:var(--glass-2);
    border:1px solid rgba(255,255,255,0.02);
    box-shadow: var(--card);
  }
  .subject h3{margin:0 0 8px 0; font-size:16px}
  .subject p{margin:0;color:var(--muted); font-size:13px}

  /* expand */
  details{background:transparent; border-radius:10px}
  summary{list-style:none; cursor:pointer; outline:none; display:flex; justify-content:space-between; align-items:center; padding:8px 12px; border-radius:10px}
  summary::-webkit-details-marker{display:none}
  .topic-body{padding:10px 12px; color:var(--muted); font-size:13px; border-top:1px dashed rgba(255,255,255,0.02); margin-top:8px}

  /* quiz */
  .quiz{display:flex; flex-direction:column; gap:10px}
  .q-btn{background:transparent; border:1px solid rgba(255,255,255,0.04); padding:10px; border-radius:10px; color:var(--muted); text-align:left}
  .q-btn.correct{border-color:rgba(34,211,238,0.6); background:linear-gradient(90deg, rgba(34,211,238,0.04), transparent)}
  .q-btn.wrong{border-color:rgba(239,68,68,0.4); background:linear-gradient(90deg, rgba(239,68,68,0.03), transparent)}
  .result{padding:12px;border-radius:10px;background:rgba(255,255,255,0.02); color:var(--muted)}

  footer{max-width:1100px;margin:28px auto;color:var(--muted); padding:18px; text-align:center; font-size:13px}
  a.link{color:var(--accent1); text-decoration:none}

  /* small visualization */
  .viz{height:220px; border-radius:10px; overflow:hidden; background:linear-gradient(180deg, rgba(12,14,26,0.6), rgba(6,8,20,0.4)); display:flex; align-items:center; justify-content:center; border:1px solid rgba(255,255,255,0.02)}
  .small{font-size:12px;color:var(--muted)}
</style>
</head>
<body>

<header>
  <div class="brand">
    <div class="logo" aria-hidden="true">
      <!-- simple SVG logo for SHERMODZ -->
      <svg viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="SHERMODZ logo">
        <defs>
          <linearGradient id="g" x1="0" x2="1" y1="0" y2="1">
            <stop offset="0" stop-color="#6ee7ff"/>
            <stop offset="1" stop-color="#a78bfa"/>
          </linearGradient>
        </defs>
        <rect x="4" y="4" width="56" height="56" rx="12" fill="url(#g)" opacity="0.12"/>
        <path d="M20 44c5-8 12-14 24-10" stroke="url(#g)" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
        <circle cx="22" cy="22" r="4" fill="#6ee7ff"/>
        <circle cx="42" cy="30" r="5" fill="#a78bfa"/>
      </svg>
    </div>
    <div>
      <h1>SHERMODZ</h1>
      <div class="tagline">Imagination → Science → Invention</div>
    </div>
  </div>

  <nav>
    <a href="#about">About</a>
    <a href="#subjects">Subjects</a>
    <a href="#learn">Learn</a>
    <a href="#quiz">Quiz</a>
    <a class="outline" href="#contact">Contact</a>
  </nav>
</header>

<main>
  <section class="hero card" id="about" aria-labelledby="hero-title">
    <div>
      <h2 id="hero-title">Welcome to SHERMODZ — Community for Scientific Imagination</h2>
      <p>
        This is the community for sharing incredible scientific knowledge and building an out-of-the-box mentality.
        We explore new technologies discovered by SHERMODZ, publish projects, theories, experiments, and practical solutions.
      </p>

      <div class="motto">
        "Imagination is more important than knowledge, knowledge is limited but imagination encircles the world 🌎"
        <br>
        "Science is not a subject, it is a way to see the world"
      </div>

      <div class="actions">
        <a class="btn" href="https://shermodz.blogspot.com" target="_blank" rel="noopener">Visit Blog</a>
        <a class="outline" href="https://youtube.com/@shermodz" target="_blank" rel="noopener">YouTube Channel</a>
      </div>

      <div class="links small">
        <div><strong>Founder</strong>: Aswin B S — The scientific guide turning imagination into real inventions</div>
        <div style="margin-top:8px"><strong>Join:</strong>
          <a class="link" href="https://whatsapp.com/channel/0029VbB594THgZWaplNfWj2L" target="_blank">WhatsApp Channel</a> ·
          <a class="link" href="https://aratt.ai/@shermodz" target="_blank">Aratt.ai</a> ·
          <a class="link" href="https://orcid.org/0009-0000-4201-8418" target="_blank">ORCID</a>
        </div>
      </div>
    </div>

    <aside class="card" aria-label="Quick actions">
      <div style="display:flex;flex-direction:column;gap:12px">
        <div>
          <strong style="color:var(--accent1)">What we teach</strong>
          <div class="small" style="margin-top:6px">Classical physics · Quantum mechanics · Relativity · Engineering · Chemistry · Materials · Electronics · AI · Psychology</div>
        </div>

        <div>
          <strong style="color:var(--accent2)">Featured</strong>
          <div class="small" style="margin-top:6px">Interactive lessons · Live simulations · Quizzes · Research notes · Project demos</div>
        </div>

        <div class="viz" id="viz">
          <canvas id="c" width="380" height="200"></canvas>
        </div>
      </div>
    </aside>
  </section>

  <hr style="border:none;height:18px"/>

  <section id="subjects">
    <h3>Subjects and Learning Areas</h3>
    <div class="grid">
      <!-- each subject card with summary + expandable details -->
      <div class="subject card">
        <h3>Classical Physics</h3>
        <p>Mechanics, waves, thermodynamics, electromagnetism, and foundational equations of motion.</p>
        <details>
          <summary>
            <span>Overview</span><strong style="color:var(--accent1)">Open</strong>
          </summary>
          <div class="topic-body">
            Key equations: Newton's laws, conservation of energy, momentum, wave equation. Visual demos include projectile motion, pendulum simulation, and harmonic oscillators.
          </div>
        </details>
      </div>

      <div class="subject card">
        <h3>Theoretical Physics</h3>
        <p>Formal frameworks that underpin models for particles, fields, and cosmic evolution.</p>
        <details>
          <summary><span>Overview</span><strong style="color:var(--accent1)">Open</strong></summary>
          <div class="topic-body">
            Topics include Lagrangian and Hamiltonian formalisms, symmetry and conservation laws, group theory foundations, and modern field theory motifs.
          </div>
        </details>
      </div>

      <div class="subject card">
        <h3>Quantum Mechanics</h3>
        <p>Wavefunctions, operators, measurement, entanglement, and the structure of matter at the smallest scales.</p>
        <details>
          <summary><span>Overview</span><strong style="color:var(--accent1)">Open</strong></summary>
          <div class="topic-body">
            Concepts: Schrödinger equation, observables, spin, quantum statistics, and basic experiments like double-slit, Stern-Gerlach, and hydrogen spectrum.
          </div>
        </details>
      </div>

      <div class="subject card">
        <h3>Relativity</h3>
        <p>Special and general relativity: space-time, time dilation, gravity as geometry, and cosmological implications.</p>
        <details>
          <summary><span>Overview</span><strong style="color:var(--accent1)">Open</strong></summary>
          <div class="topic-body">
            Sections include Lorentz transforms, Minkowski diagrams, equivalence principle, Schwarzschild metric, gravitational waves, and applications to GPS and cosmology.
          </div>
        </details>
      </div>

      <div class="subject card">
        <h3>Engineering & Electronics</h3>
        <p>Practical design, circuits, signal processing, AC machines, and device functioning.</p>
        <details>
          <summary><span>Overview</span><strong style="color:var(--accent1)">Open</strong></summary>
          <div class="topic-body">
            Learn AC vs DC, polyphase motors, power electronics basics, semiconductor devices, circuits, sensors, and microcontroller project guides.
          </div>
        </details>
      </div>

      <div class="subject card">
        <h3>Materials & Chemistry</h3>
        <p>Periodic table, inorganic chemistry, materials like graphene and carbon nanotubes, and material design principles.</p>
        <details>
          <summary><span>Overview</span><strong style="color:var(--accent1)">Open</strong></summary>
          <div class="topic-body">
            Atomic structure, bonding, crystal structures, mechanical properties, synthesis notes for advanced materials, and characterization basics.
          </div>
        </details>
      </div>

      <div class="subject card">
        <h3>Psychology & Body Language</h3>
        <p>Human behaviour, perception, and nonverbal communication—applied to science education and collaboration.</p>
        <details>
          <summary><span>Overview</span><strong style="color:var(--accent1)">Open</strong></summary>
          <div class="topic-body">
            Cognitive biases, learning psychology, experimental design for human-subject research and practical guides to reading body language in labs and presentations.
          </div>
        </details>
      </div>

      <div class="subject card">
        <h3>Fictional Tech to Reality</h3>
        <p>How to take sci-fi ideas and evaluate them scientifically to design plausible prototypes.</p>
        <details>
          <summary><span>Overview</span><strong style="color:var(--accent1)">Open</strong></summary>
          <div class="topic-body">
            Feasibility studies, scaling laws, energy budgets, and step-by-step approaches to turn imaginative concepts into research projects and prototypes.
          </div>
        </details>
      </div>

      <div class="subject card">
        <h3>AI & Computational Tools</h3>
        <p>How artificial intelligence works, modelling, simulation, and data-driven experiments.</p>
        <details>
          <summary><span>Overview</span><strong style="color:var(--accent1)">Open</strong></summary>
          <div class="topic-body">
            Intro to ML workflows, neural networks, training/testing, data ethics, and code snippets for scientific computing and visualization.
          </div>
        </details>
      </div>
    </div>
  </section>

  <hr style="border:none;height:18px"/>

  <section id="learn" class="card" style="margin-top:18px">
    <h3>Learning Hub</h3>
    <p style="color:var(--muted)">Interactive lessons, experiment ideas, and live demos. Start with structured modules or explore quick interactive demos below.</p>

    <div style="display:grid; grid-template-columns:1fr 360px; gap:16px; margin-top:14px">
      <div>
        <h4 style="margin:0 0 10px 0">Featured modules</h4>
        <div style="display:flex;flex-direction:column;gap:12px">
          <div class="card">
            <strong>Special & General Relativity</strong>
            <div class="small" style="margin-top:6px">Time dilation, Lorentz transform, metric concepts, gravitational redshift, and practical calculation examples with diagrams and code.</div>
          </div>

          <div class="card">
            <strong>Standard Model & Quantum Field Theory</strong>
            <div class="small" style="margin-top:6px">Overview of particles, interactions, QED, QCD, electroweak unification, and current open problems like quantum gravity and unification attempts.</div>
          </div>

          <div class="card">
            <strong>Materials</strong>
            <div class="small" style="margin-top:6px">Graphene, carbon nanotubes, synthesis overview, mechanical and electrical properties, and device integration examples.</div>
          </div>

          <div class="card">
            <strong>Electronics & Spectra</strong>
            <div class="small" style="margin-top:6px">Discharge tube, hydrogen spectrum basics, semiconductor experiments, and instrumentation notes for safe classroom demos.</div>
          </div>
        </div>
      </div>

      <aside>
        <h4 style="margin:0 0 10px 0">Interactive</h4>

        <div class="card" style="margin-bottom:12px">
          <strong>Electron/Photon Visual Demo</strong>
          <div class="small" style="margin-top:8px">A small canvas visualization illustrates particle-like motion and simple wave interference patterns.</div>
        </div>

        <div class="card">
          <strong>Quick search</strong>
          <input id="search" placeholder="Search topics, e.g., 'Lorentz' or 'graphene'" style="width:100%;margin-top:8px;padding:8px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);background:transparent;color:inherit" />
          <div id="searchResults" class="small" style="margin-top:8px"></div>
        </div>
      </aside>
    </div>
  </section>

  <hr style="border:none;height:18px"/>

  <section id="quiz" class="card" style="margin-top:18px">
    <h3>Quick Quiz</h3>
    <p class="small" style="margin-top:6px;color:var(--muted)">Test yourself. Immediate feedback and short explanations help learning retention.</p>

    <div class="quiz" id="quizArea" style="margin-top:12px">
      <div id="qtext"><strong>Question</strong>: According to special relativity, which of the following is invariant for all inertial observers?</div>

      <div id="choices">
        <button class="q-btn" data-c="0">A: Time intervals between two events</button>
        <button class="q-btn" data-c="1">B: Spatial distance between two events (simultaneous in one frame)</button>
        <button class="q-btn" data-c="2">C: The spacetime interval between two events</button>
        <button class="q-btn" data-c="3">D: Velocity of a moving object</button>
      </div>

      <div id="out" class="result" style="display:none"></div>
    </div>
  </section>

  <hr style="border:none;height:18px"/>

  <section id="extras" class="card" style="margin-top:18px">
    <h3>Deep Topics & Guides</h3>
    <p style="color:var(--muted)">Curated guided reading and summaries for advanced subjects. Each topic contains definitions, important equations, historical notes, and visual aids.</p>

    <details open>
      <summary style="font-weight:700">Time Travel and Scientific Discussion</summary>
      <div class="topic-body">
        Time travel is a speculative subject with scientific viewpoints drawn mostly from general relativity and quantum gravity research. Common scientifically-discussed ideas include closed timelike curves, wormholes under exotic energy conditions, and Gödel-type rotating universes. Each idea requires careful mathematical treatment and faces major physical and practical constraints.
      </div>
    </details>

    <details>
      <summary style="font-weight:700">Grand Unified Theories and Theory of Everything</summary>
      <div class="topic-body">
        GUTs attempt to unify strong, weak, and electromagnetic forces; quantum gravity aims at incorporating gravity with quantum mechanics. Research includes string theory, loop quantum gravity, and various unification models. Overviews include what is known, experimental limits, and open questions.
      </div>
    </details>

    <details>
      <summary style="font-weight:700">Historical Notes</summary>
      <div class="topic-body">
        Short biographies and major contributions: Newton, Maxwell, Einstein, Planck, Feynman, Dirac, Tesla, Curie, and modern contributors. Contextual history connects discoveries to practical technologies.
      </div>
    </details>
  </section>

  <hr style="border:none;height:18px"/>

  <section id="contact" class="card" style="margin-top:18px">
    <h3>Contact & Contribution</h3>
    <p class="small" style="color:var(--muted)">Submit projects, experiments, and research notes. Use the links below to follow and join discussions.</p>
    <div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:10px">
      <a class="btn" href="https://shermodz.blogspot.com" target="_blank">Blog</a>
      <a class="outline" href="https://whatsapp.com/channel/0029VbB594THgZWaplNfWj2L" target="_blank">WhatsApp</a>
      <a class="outline" href="https://aratt.ai/@shermodz" target="_blank">Aratt.ai</a>
      <a class="outline" href="https://orcid.org/0009-0000-4201-8418" target="_blank">ORCID</a>
    </div>
    
<!-- SHERMODZ profile badge -->
<style>
  .shermodz-badge{display:flex;align-items:center;gap:12px;font-family:Inter,system-ui,Arial;color:#e6eef8}
  .shermodz-avatar{
    width:88px;height:88px;border-radius:50%;overflow:hidden;
    box-shadow:0 8px 24px rgba(2,6,23,0.6);
    border:2px solid rgba(110,231,255,0.08);background:#071022;
    display:inline-block;flex-shrink:0;
  }
  .shermodz-avatar img{width:100%;height:100%;object-fit:cover;display:block}
  .shermodz-meta{line-height:1}
  .shermodz-title{font-weight:800;font-size:18px;color:#aee9ff;margin:0}
  .shermodz-sub{font-size:12px;color:#9aa7c7;margin-top:4px}
</style>

<div class="shermodz-badge">
  <span class="shermodz-avatar" aria-hidden="true">
    <img src="PROFILE_IMAGE_URL" alt="SHERMODZ Resources logo"/>
  </span>
  <div class="shermodz-meta">
    <div class="shermodz-title">SHERMODZ RESOURCES</div>
    <div class="shermodz-sub">Imagination → Science → Invention · Founder: Aswin B S</div>
  </div>
</div>
<!-- SHERMODZ Profile Badge -->
<style>
  .shermodz-badge {
    --bg1: #0b1020;
    --grad1: linear-gradient(135deg,#6ee7ff 0%,#8b6bff 45%,#ff6ec7 100%);
    --glass: rgba(255,255,255,0.03);
    --muted: #b9c8de;
    --accent: #6ee7ff;
    display:flex;
    gap:16px;
    align-items:center;
    padding:14px;
    border-radius:14px;
    background: linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.00));
    border:1px solid rgba(255,255,255,0.04);
    max-width:760px;
    box-shadow: 0 10px 40px rgba(6,8,20,0.7);
    font-family: Inter,Segoe UI,Roboto,Arial, sans-serif;
    color:#e9f5ff;
  }

  .shermodz-avatar {
    width:120px;
    height:120px;
    flex:0 0 120px;
    border-radius:50%;
    padding:6px;
    background: conic-gradient(from 180deg at 50% 50%, #6ee7ff, #8b6bff, #ff6ec7, #6ee7ff);
    display:flex;
    align-items:center;
    justify-content:center;
    box-shadow: 0 8px 30px rgba(99,102,241,0.12), inset 0 1px 0 rgba(255,255,255,0.06);
    transition: transform .28s ease, box-shadow .28s ease;
  }

  .shermodz-avatar img {
    width:100%;
    height:100%;
    border-radius:50%;
    object-fit:cover;
    display:block;
    background:var(--bg1);
    border:4px solid rgba(11,16,32,0.55);
  }

  .shermodz-avatar:hover { transform: translateY(-6px) scale(1.02); box-shadow: 0 18px 50px rgba(105,92,255,0.22); }

  .shermodz-meta { display:flex; flex-direction:column; gap:6px; min-width:0 }
  .shermodz-title {
    font-size:20px;
    font-weight:800;
    letter-spacing:0.6px;
    display:flex;
    align-items:center;
    gap:10px;
  }
  .brand-badge {
    background:var(--grad1);
    -webkit-background-clip:text;
    background-clip:text;
    color:transparent;
    font-weight:900;
    font-size:20px;
  }
  .shermodz-sub { font-size:13px; color:var(--muted); margin-top:2px }
  .shermodz-desc { color:#cfeeff; font-size:13px; max-width:520px; line-height:1.4 }

  .links { display:flex; gap:8px; margin-top:8px; flex-wrap:wrap }
  .link-btn {
    padding:8px 12px;
    border-radius:10px;
    font-weight:700;
    font-size:13px;
    color:#021025;
    background: linear-gradient(90deg,#a78bfa,#6ee7ff);
    text-decoration:none;
    box-shadow: 0 8px 30px rgba(106,90,255,0.08);
  }
  .soft-btn {
    padding:8px 12px;
    border-radius:10px;
    font-weight:700;
    font-size:13px;
    color:var(--muted);
    background: rgba(255,255,255,0.02);
    border:1px solid rgba(255,255,255,0.04);
    text-decoration:none;
  }

  /* small responsive */
  @media (max-width:720px) {
    .shermodz-badge { flex-direction:column; align-items:center; text-align:center; padding:16px }
    .shermodz-avatar { width:110px; height:110px; flex:0 0 110px }
    .shermodz-meta { align-items:center }
    .shermodz-desc { max-width:100% }
  }
</style>

<div class="shermodz-badge" role="region" aria-label="SHERMODZ profile">
  <div class="shermodz-avatar" aria-hidden="true">
    <!-- Replace PROFILE_IMAGE_URL with your image link -->
    <img src="PROFILE_IMAGE_URL" alt="SHERMODZ Resources profile picture">
  </div>

  <div class="shermodz-meta">
    <div class="shermodz-title">
      <span class="brand-badge">SHERMODZ</span>
      <span style="font-weight:600; font-size:13px; color:#bcdcff;">RESOURCES</span>
    </div>

    <div class="shermodz-sub">Founder: Aswin B S · Imagination → Science → Invention</div>

    <div class="shermodz-desc">
      A community for sharing scientific knowledge and turning imaginative ideas into real inventions. Explore physics, materials, electronics, AI, experiments, and interactive lessons.
    </div>

    <div class="links" aria-hidden="false">
      <a class="link-btn" href="https://shermodz.blogspot.com" target="_blank" rel="noopener">Visit Blog</a>
      <a class="soft-btn" href="https://youtube.com/@shermodz" target="_blank" rel="noopener">YouTube</a>
      <a class="soft-btn" href="https://orcid.org/0009-0000-4201-8418" target="_blank" rel="noopener">ORCID</a>
    </div>
  </div>
</div>
