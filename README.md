<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>SHERMODZ — Science, Imagination, Invention</title>
  <meta name="description" content="SHERMODZ — community to share scientific knowledge, build out-of-the-box solutions, learning, quizzes, interactive lessons and research." />
  <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><rect width='100' height='100' fill='%23071A3A'/><text x='50' y='58' font-size='44' text-anchor='middle' fill='%23B39DFF'>S</text></svg>">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#080612;
      --card:#0d1224;
      --muted:#9aa2c7;
      --accent1:#5b6cff; /* blue */
      --accent2:#8a4bff; /* violet */
      --glass: rgba(255,255,255,0.03);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,Arial;background:linear-gradient(180deg,var(--bg),#04030a);color:#e6eef9}
    a{color:var(--accent1);text-decoration:none}
    header{position:sticky;top:0;backdrop-filter:blur(6px);z-index:40;border-bottom:1px solid rgba(255,255,255,0.03)}
    .container{max-width:1100px;margin:0 auto;padding:28px}
    .nav{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent1),var(--accent2));display:grid;place-items:center;font-weight:800;color:#fff;font-size:20px;box-shadow:0 6px 18px rgba(138,75,255,0.14)}
    nav ul{display:flex;gap:16px;align-items:center;margin:0;padding:0;list-style:none}
    .cta{background:linear-gradient(90deg,var(--accent1),var(--accent2));padding:10px 14px;border-radius:10px;font-weight:700;color:#fff}

    .hero{padding:60px 0;display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center}
    .hero h1{font-size:34px;line-height:1.02;margin:0 0 12px}
    .hero p.lead{color:var(--muted);margin:0 0 18px}
    .badges{display:flex;gap:8px;flex-wrap:wrap}
    .badge{background:linear-gradient(90deg,rgba(91,108,255,0.12),rgba(138,75,255,0.08));padding:8px 12px;border-radius:999px;font-weight:600;color:#dfe7ff}

    .card{background:linear-gradient(180deg,var(--card),rgba(7,9,20,0.6));border-radius:14px;padding:18px;border:1px solid rgba(255,255,255,0.03)}
    .subjects{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin-top:18px}
    .subject{padding:14px;border-radius:12px;background:linear-gradient(180deg,rgba(255,255,255,0.012),transparent);border:1px solid rgba(255,255,255,0.02)}
    .subject h4{margin:0 0 6px}
    .muted{color:var(--muted);font-size:13px}

    /* History timeline */
    .timeline{margin-top:20px;border-left:2px dashed rgba(255,255,255,0.03);padding-left:18px}
    .timeline .item{margin-bottom:18px}
    details summary{cursor:pointer;outline:none}

    /* Quiz */
    .quiz{display:grid;gap:12px}
    .question{background:var(--glass);padding:12px;border-radius:10px}
    .options{display:flex;flex-direction:column;gap:8px}
    .opt{padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);cursor:pointer}
    .opt:hover{transform:translateY(-2px)}

    /* Layout */
    main{padding:18px 0}
    .two{display:grid;grid-template-columns:1fr 360px;gap:20px}
    footer{padding:26px 0;margin-top:20px;border-top:1px solid rgba(255,255,255,0.02)}

    /* responsive */
    @media(max-width:900px){.hero{grid-template-columns:1fr;}.two{grid-template-columns:1fr}.nav ul{display:none}}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <div class="logo">S</div>
        <div>
          <div style="font-weight:800">SHERMODZ</div>
          <div style="font-size:12px;color:var(--muted)">Imagination → Science → Invention</div>
        </div>
      </div>
      <nav>
        <ul>
          <li><a href="#learn">Learn</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#quiz">Quiz</a></li>
          <li><a href="#about">About</a></li>
          <li><a class="cta" href="#join">Join</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div>
        <h1>SHERMODZ — Science as an eye to see the world and a hand to build it</h1>
        <p class="lead">This community shares incredible scientific knowledge and builds out-of-the-box solutions. We blend classical theory, modern physics, engineering and hands-on experiments to turn imagination into reality.</p>
        <div class="badges">
          <div class="badge">Dark theme • Blue &amp; Violet</div>
          <div class="badge">Interactive lessons</div>
          <div class="badge">Quizzes &amp; experiments</div>
          <div class="badge">Open research • ORCID</div>
        </div>

        <div style="margin-top:18px" class="card">
          <h3>Quick links</h3>
          <ul style="margin:8px 0 0;padding-left:18px;color:var(--muted)">
            <li><a href="https://shermodz.blogspot.com" target="_blank">Website blog</a></li>
            <li><a href="https://whatsapp.com/channel/0029VbB594THgZWaplNfWj2L" target="_blank">WhatsApp channel</a></li>
            <li><a href="https://aratt.ai/@shermodz" target="_blank">Aratt channel</a></li>
            <li><a href="https://orcid.org/0009-0000-4201-8418" target="_blank">ORCID</a></li>
            <li><a href="https://youtube.com/@shermodz" target="_blank">YouTube</a></li>
          </ul>
        </div>
      </div>

      <aside>
        <div class="card">
          <h3>Founder</h3>
          <div style="display:flex;gap:12px;align-items:center">
            <div style="width:64px;height:64px;border-radius:12px;background:linear-gradient(135deg,var(--accent2),var(--accent1));display:grid;place-items:center;font-weight:800;color:#fff">A</div>
            <div>
              <div style="font-weight:700">Aswin B S</div>
              <div class="muted">The scientific guy who makes real inventions from imagination</div>
            </div>
          </div>
          <p style="margin-top:12px" class="muted">"Imagination is more important than knowledge..."<br>"Science is not a subject, it is a way to see the world."</p>

          <hr style="border:none;border-top:1px solid rgba(255,255,255,0.03);margin:12px 0">
          <strong>Join</strong>
          <p class="muted">Subscribe to updates and follow our channels for experiments, projects and lessons.</p>
          <a class="cta" href="#join">Subscribe</a>
        </div>

        <div style="margin-top:14px" class="card">
          <h4>Featured project</h4>
          <p class="muted">SheraFuser — conceptual fusion research (prototype &amp; theories). Click projects to read details.</p>
        </div>
      </aside>
    </section>

    <section id="learn" class="card">
      <h2>Learn — Subjects &amp; interactive lessons</h2>
      <p class="muted">Click any subject to expand history, theory, key equations, experiments and interactive links.</p>

      <div class="subjects">
        <article class="subject">
          <h4>Classical physics</h4>
          <div class="muted">Newtonian mechanics, Lagrangian &amp; Hamiltonian formalisms, fluid mechanics.</div>
          <details>
            <summary class="muted">Contents</summary>
            <ul>
              <li>Newton's laws, kinematics, dynamics (F=ma)</li>
              <li>Euler-Lagrange equations, conservation laws</li>
              <li>Classical equations: Coulomb's law, Biot–Savart, Gauss' law</li>
            </ul>
          </details>
        </article>

        <article class="subject">
          <h4>Theoretical physics</h4>
          <div class="muted">Symmetries, field theory, and speculative models.</div>
          <details>
            <summary class="muted">Contents</summary>
            <ul>
              <li>Standard Model overview, gauge symmetries</li>
              <li>Grand Unified Theories, attempts at unification</li>
              <li>Quantum gravity approaches (string theory, loop quantum gravity)</li>
            </ul>
          </details>
        </article>

        <article class="subject">
          <h4>Quantum mechanics</h4>
          <div class="muted">Superposition, entanglement, measurement theory and applications.</div>
          <details>
            <summary class="muted">Contents</summary>
            <ul>
              <li>Wavefunctions, Schrödinger equation, operators</li>
              <li>Quantum electrodynamics (QED) basics</li>
              <li>Quantum computing primer</li>
            </ul>
          </details>
        </article>

        <article class="subject">
          <h4>Relativity</h4>
          <div class="muted">Special &amp; General Relativity, spacetime geometry and gravitational theory.</div>
          <details>
            <summary class="muted">Contents</summary>
            <ul>
              <li>Einstein field equations (overview)</li>
              <li>Time dilation, Lorentz transformations</li>
              <li>Ten scientifically plausible time-travel concepts (explained)</li>
            </ul>
          </details>
        </article>

        <article class="subject">
          <h4>Engineering</h4>
          <div class="muted">Design methods, prototyping, and applied materials.</div>
          <details>
            <summary class="muted">Contents</summary>
            <ul>
              <li>Systems engineering, CAD, testing protocols</li>
              <li>Electronic design, PCB basics, power systems</li>
            </ul>
          </details>
        </article>

        <article class="subject">
          <h4>Inorganic chemistry</h4>
          <div class="muted">Periodic trends, bonding, materials chemistry and synthesis.</div>
        </article>

        <article class="subject">
          <h4>Material design</h4>
          <div class="muted">Graphene, carbon nanotubes, composites and fabrication techniques.</div>
        </article>

        <article class="subject">
          <h4>Fictional → Reality</h4>
          <div class="muted">Turning sci‑fi concepts into engineering thought experiments and prototypes.</div>
        </article>

        <article class="subject">
          <h4>Electronics &amp; Electrical</h4>
          <div class="muted">Devices, AC motors, Tesla, discharge tubes, spectra and instrumentation.</div>
        </article>

        <article class="subject">
          <h4>Psychology</h4>
          <div class="muted">Body language, cognitive bias, scientific thinking and problem solving.</div>
        </article>
      </div>

      <div style="margin-top:16px;display:flex;gap:12px;flex-wrap:wrap">
        <a class="cta" href="#projects">See projects</a>
        <a style="padding:10px 12px;border-radius:10px;border:1px solid rgba(255,255,255,0.03)" href="#quiz">Take a quiz</a>
      </div>
    </section>

    <div class="two" style="margin-top:18px">
      <section id="projects" class="card">
        <h2>Projects &amp; Research</h2>
        <p class="muted">Space for project pages. Each project gets its own subpage (Markdown/HTML) with diagrams, files and logs.</p>

        <details open>
          <summary>SHERAFUSER (conceptual)</summary>
          <div class="muted" style="margin-top:8px">High-level description of conceptual fusion designs, thermoelectric capture, vacuum insulation and safety notes.</div>
        </details>

        <details>
          <summary>Project 369 (fuel-free flying vehicle)</summary>
          <div class="muted" style="margin-top:8px">Overview of design goals, prototypes and demonstrators. Notes on safety and ethics.</div>
        </details>

        <details>
          <summary>CVD Carbon Nanotubes (low-cost)</summary>
          <div class="muted" style="margin-top:8px">Process descriptions, low-cost recipes and laboratory safety reminders.</div>
        </details>

        <hr style="border:none;border-top:1px solid rgba(255,255,255,0.03);margin:12px 0">
        <h4>Project files</h4>
        <p class="muted">You can link GitHub repos, PDF papers and datasets here. Each project page supports embedded images and YouTube videos for live lessons.</p>
      </section>

      <aside class="card">
        <h3 id="quiz">Interactive quiz — Quick test</h3>
        <div class="quiz" id="quiz-area">
          <div class="question" id="q-text">Loading question...</div>
          <div class="options" id="q-options"></div>
          <div style="display:flex;gap:8px;align-items:center;margin-top:8px">
            <button id="next" class="cta">Next</button>
            <div class="muted" id="score">Score: 0 / 0</div>
          </div>
        </div>
      </aside>
    </div>

    <section class="card" style="margin-top:18px">
      <h2>History &amp; Foundations</h2>
      <p class="muted">Curated timelines and concise histories for each discipline. Expand any timeline below.</p>

      <div class="timeline">
        <div class="item">
          <details>
            <summary><strong>Classical physics</strong> — Ancient to 19th century</summary>
            <p class="muted">From Aristotle and Archimedes to Newton and Maxwell. Key equations: Newton's laws, Maxwell's equations, conservation of energy.</p>
          </details>
        </div>

        <div class="item">
          <details>
            <summary><strong>Quantum revolution</strong> — 20th century</summary>
            <p class="muted">Planck, Einstein, Schrödinger and Dirac. Development of quantum theory, QED and the Standard Model.</p>
          </details>
        </div>

        <div class="item">
          <details>
            <summary><strong>Modern materials &amp; nanotech</strong></summary>
            <p class="muted">Discovery of graphene, synthesis of carbon nanotubes and advances in materials engineering enabling today's prototypes.</p>
          </details>
        </div>
      </div>
    </section>

    <section id="about" class="card" style="margin-top:18px">
      <h2>About SHERMODZ</h2>
      <p class="muted">SHERMODZ is a community platform to learn, publish and prototype. Founder: <strong>Aswin B S</strong>. Mission: Use scientific thinking to solve real-life problems and publish open research.</p>

      <h3>Detailed topics included</h3>
      <ul>
        <li>Special &amp; General Relativity — derivations, Lorentz transforms, metric tensor overview</li>
        <li>Standard Model, QCD, QED — particle content, interactions and Feynman diagram examples</li>
        <li>Ten plausible time-travel ideas — wormholes, closed timelike curves, relativistic travel, cosmic strings (explanations, not instructions)</li>
        <li>Complete periodic table overview, bonding and reactivity</li>
        <li>Nikola Tesla: AC current, polyphase systems and motors</li>
        <li>AI basics: structure, learning algorithms and practical demos</li>
        <li>Carbon nanotubes &amp; graphene: structure, synthesis and properties</li>
        <li>Electronics: discharge tubes, hydrogen spectrum, instrumentation</li>
      </ul>

      <p class="muted">Important: Some topics (weapons, harmful processes) are covered only from an academic / historical / safety perspective and will not include operational instructions.</p>
    </section>

    <section id="join" class="card" style="margin-top:18px">
      <h2>Get involved</h2>
      <p class="muted">Ways to contribute: write tutorials, publish projects, contribute data, volunteer as a mentor.</p>
      <form id="subscribe" style="display:grid;grid-template-columns:1fr auto;gap:8px;max-width:720px;margin-top:10px">
        <input id="email" placeholder="Your email or channel link" style="padding:12px;border-radius:8px;border:1px solid rgba(255,255,255,0.03);background:transparent;color:inherit">
        <button class="cta" type="button" onclick="subscribe()">Subscribe</button>
      </form>
      <p id="submsg" class="muted" style="margin-top:8px"></p>
    </section>

  </main>

  <footer>
    <div class="container">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div>
          <strong>SHERMODZ</strong>
          <div class="muted">Imagination is more important than knowledge...</div>
        </div>
        <div class="muted">Links: <a href="https://shermodz.blogspot.com">Blog</a> • <a href="https://youtube.com/@shermodz">YouTube</a> • <a href="https://orcid.org/0009-0000-4201-8418">ORCID</a></div>
      </div>
    </div>
  </footer>

  <script>
    // --- Simple quiz data (expandable) ---
    const quiz = [
      {q:"Who formulated the three classical laws of motion?",opts:["Einstein","Newton","Maxwell","Planck"],a:1},
      {q:"What is the fundamental equation of non-relativistic quantum mechanics?",opts:["Maxwell's equations","Schrödinger equation","Navier–Stokes equation","Lorentz force law"],a:1},
      {q:"Which material is a single layer of carbon atoms arranged in a hexagonal lattice?",opts:["Diamond","Graphene","Silicon","Boron Nitride"],a:1}
    ];

    let index = 0, score=0, total=0;
    const qText = document.getElementById('q-text');
    const qOpts = document.getElementById('q-options');
    const scoreEl = document.getElementById('score');

    function render(){
      const item = quiz[index%quiz.length];
      qText.textContent = (index+1)+'. '+item.q;
      qOpts.innerHTML = '';
      item.opts.forEach((opt,i)=>{
        const btn = document.createElement('div');
        btn.className='opt';
        btn.textContent = opt;
        btn.onclick = ()=>{ choose(i,item.a,btn) };
        qOpts.appendChild(btn);
      });
      scoreEl.textContent = `Score: ${score} / ${total}`;
    }

    function choose(i,ans,btn){
      total++;
      if(i===ans){ score++; btn.style.borderColor='lime'; }
      else{ btn.style.borderColor='crimson'; }
      // disable
      Array.from(qOpts.children).forEach(c=>c.onclick=null);
      scoreEl.textContent = `Score: ${score} / ${total}`;
    }

    document.getElementById('next').onclick = ()=>{ index++; render(); };
    render();

    // Subscribe (placeholder)
    function subscribe(){
      const email = document.getElementById('email').value.trim();
      const msg = document.getElementById('submsg');
      if(!email){ msg.textContent = 'Enter an email or channel link.'; return }
      msg.textContent = 'Thanks! Saved locally (copy to your backend to collect).';
      // This demo does not send to server. Replace with your backend / Mailchimp / Google Form.
      localStorage.setItem('shermodz_sub_'+Date.now(), email);
    }

    // Add small keyboard nav
    document.addEventListener('keyup', e=>{ if(e.key==='q') window.location.hash='#quiz' })
  </script>
</body>
</html>
