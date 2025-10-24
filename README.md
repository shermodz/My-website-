<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>SHERMODZ Scientific Community</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@700&family=Roboto&display=swap');

  :root {
    --bg-color: #121212;
    --primary-color: #4a00e0;
    --secondary-color: #8a2be2;
    --accent-color: #3b82f6;
    --text-color: #e0e0e0;
    --highlight-color: #7f00ff;
    --link-color: #90caf9;
    --border-color: #2a2a2a;
    --quiz-bg: #1f1f40;
  }

  body, html {
    margin: 0; padding: 0; background: var(--bg-color); color: var(--text-color);
    font-family: 'Roboto', sans-serif;
    scroll-behavior: smooth;
  }
  a {
    color: var(--link-color);
    text-decoration: none;
  }
  a:hover {
    color: var(--accent-color);
  }
  h1, h2, h3 {
    font-family: 'Orbitron', sans-serif;
    color: var(--primary-color);
    text-shadow: 0 0 10px var(--highlight-color);
  }

  header {
    display: flex; align-items: center; padding: 1rem 2rem;
    background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
    position: sticky; top: 0; z-index: 1000;
    box-shadow: 0 2px 10px rgba(0,0,0,0.7);
  }
  header img.logo {
    height: 60px;
    margin-right: 1rem;
    border-radius: 8px;
  }
  header h1 {
    font-size: 1.8rem;
  }

  nav {
    margin-left: auto;
  }
  nav a {
    margin-left: 1.5rem;
    font-weight: 600;
    font-size: 1rem;
    letter-spacing: 0.05em;
  }

  main {
    max-width: 1200px;
    margin: 2rem auto;
    padding: 0 1rem;
  }

  section {
    margin-bottom: 3rem;
    border-radius: 10px;
    padding: 1.5rem 2rem;
    background: #1a1a2e;
    box-shadow: 0 0 20px #4a00e0bb;
    transition: background 0.3s ease;
  }
  section:hover {
    background: #271d4d;
  }

  ul {
    list-style-type: disc;
    margin-left: 1.5rem;
  }

  blockquote {
    font-style: italic;
    color: var(--accent-color);
    border-left: 4px solid var(--highlight-color);
    margin: 1rem 0 1rem 1rem;
    padding-left: 1rem;
  }

  .subjects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
    gap: 1.5rem;
  }
  .subject-card {
    background: #2b2b50;
    border-radius: 8px;
    padding: 1rem;
    box-shadow: 0 0 15px #7f00ffbb;
    color: var(--text-color);
  }
  .subject-card img {
    width: 100%;
    border-radius: 6px;
    margin-bottom: 1rem;
  }
  .subject-card h3 {
    margin-top: 0;
  }

  #quiz-section {
    background: var(--quiz-bg);
    color: var(--text-color);
    border-radius: 8px;
    padding: 1rem;
  }
  #quiz-section h2 {
    color: var(--accent-color);
  }
  #quiz-section button {
    margin-top: 1rem;
    background: var(--primary-color);
    color: white;
    border: none;
    padding: 0.6rem 1.2rem;
    border-radius: 5px;
    cursor: pointer;
    font-weight: 600;
    font-family: 'Orbitron', sans-serif;
    transition: background 0.3s ease;
  }
  #quiz-section button:hover {
    background: var(--secondary-color);
  }

  footer {
    background: #0e0e20;
    color: var(--text-color);
    text-align: center;
    padding: 1rem 2rem;
    font-size: 0.9rem;
  }
  footer a {
    margin: 0 0.8rem;
    font-weight: 600;
  }
</style>
</head>
<body>

<header>
  <img src="1000003523.jpg" alt="SHERMODZ Logo" class="logo" />
  <h1>SHERMODZ</h1>
  <nav>
    <a href="#purpose">Purpose</a>
    <a href="#subjects">Subjects</a>
    <a href="#topics">Theories & History</a>
    <a href="#quiz">Quiz</a>
    <a href="#founder">Founder</a>
    <a href="#links">Links</a>
  </nav>
</header>

<main>
  <section id="purpose">
    <h2>Purpose of SHERMODZ</h2>
    <p>This is the community for sharing incredible scientific knowledge and fostering an out-of-the-box mentality. SHERMODZ showcases new technologies discovered by Aswin B S and helps you explore scientific questions in:</p>
    <ul>
      <li>Classical Physics</li>
      <li>Theoretical Physics</li>
      <li>Quantum Mechanics</li>
      <li>Relativity</li>
      <li>Engineering</li>
      <li>Psychology</li>
      <li>Inorganic Chemistry</li>
      <li>Material Design</li>
      <li>Fictional Technology to Reality</li>
      <li>Electronics & Electrical</li>
    </ul>
    <p>SHERMODZ builds scientific thinking and solves real-life problems through science because <strong>"Science is not a subject, it is a way to see the world."</strong></p>
    <blockquote>
      "Imagination is more important than knowledge, knowledge is limited but imagination encircles the world 🌎" <br/>
      "Science is not a subject; it is a way to see and invent the world."
    </blockquote>
    <p><strong>SHERMODZ will guide you to use science as an eye to see the world and a hand to build it.</strong></p>
  </section>

  <section id="subjects">
    <h2>Learn & Explore</h2>
    <div class="subjects-grid">
      <div class="subject-card">
        <h3>Classical Physics</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f4/Newtons_Principia_Mathema.png/320px-Newtons_Principia_Mathema.png" alt="Newton's Principia" />
        <p>Discover the foundation laws laid by Newton, equations of motion, forces, and charge dynamics.</p>
      </div>
      <div class="subject-card">
        <h3>Theoretical Physics</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Einstein_Symbol.svg/320px-Einstein_Symbol.svg.png" alt="Einstein" />
        <p>Dive deep into modern physics: relativistic effects, special and general relativity.</p>
      </div>
      <div class="subject-card">
        <h3>Quantum Mechanics</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Double-slit_experiment_results_Tanamura_2.jpg/320px-Double-slit_experiment_results_Tanamura_2.jpg" alt="Double Slit Experiment" />
        <p>Explore quantum phenomena, the standard model, quantum electrodynamics, and gravity theories.</p>
      </div>
      <div class="subject-card">
        <h3>Engineering</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Civil_engineering_project_Turkey.jpg/320px-Civil_engineering_project_Turkey.jpg" alt="Engineering" />
        <p>Apply scientific principles to real-world building, electronics, and electrical technologies.</p>
      </div>
      <div class="subject-card">
        <h3>Psychology</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/14/Face_body_language_silhouettes.png/320px-Face_body_language_silhouettes.png" alt="Body Language" />
        <p>Explore the psychology of body language and cognitive science.</p>
      </div>
      <div class="subject-card">
        <h3>Inorganic Chemistry & Materials</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Periodic_table_large.png/320px-Periodic_table_large.png" alt="Periodic Table" />
        <p>Study periodic table, carbon nanostructures like graphene and nanotubes, and material design principles.</p>
      </div>
      <div class="subject-card">
        <h3>Fictional Tech to Reality</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/Science_Fiction.svg/320px-Science_Fiction.svg.png" alt="Sci-fi" />
        <p>Turn fiction into science: concepts on time travel, weapon tech, and futuristic devices.</p>
      </div>
      <div class="subject-card">
        <h3>Electronics & Electrical</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/64/Electronic_circuit_board.jpg/320px-Electronic_circuit_board.jpg" alt="Circuit Board" />
        <p>Understand circuitry, AC motors, polyphase current, discharge tubes, and hydrogen spectrum.</p>
      </div>
    </div>
  </section>

  <section id="topics">
    <h2>Scientific Theories & History Highlights</h2>
    <p>Explore topics such as:</p>
    <ul>
      <li>10 Scientifically Possible Ways to Travel in Time</li>
      <li>Special & General Theory of Relativity</li>
      <li>The Standard Model, Quantum Chromodynamics, Quantum Electrodynamics, Quantum Gravity</li>
      <li>Grand Unified Theory and Theory of Everything</li>
      <li>Fundamental Forces of Nature</li>
      <li>Classical Equations: Charges, Forces, Newtonian Dynamics, Laws of Motion</li>
      <li>The Periodic Table and its Elements</li>
      <li>Contributions of Nikola Tesla: AC Current and Motors, Polyphase Systems</li>
      <li>Psychology of Body Language</li>
      <li>Artificial Intelligence Workings</li>
      <li>Structure and Function of Carbon Nanotubes and Graphene</li>
      <li>Functioning of Electronic Devices, Discharge Tubes & Hydrogen Spectrum</li>
      <li>Weapon Technologies and Advanced Scientific Concepts</li>
    </ul>
  </section>

  <section id="quiz">
    <h2>Science Quiz</h2>
    <div id="quiz-section">
      <div id="quiz-container">
        <p id="question"></p>
        <div id="choices"></div>
        <button id="next-btn" style="display:none;">Next Question</button>
        <p id="result"></p>
      </div>
    </div>
  </section>

  <section id="founder">
    <h2>Founder of SHERMODZ</h2>
    <p><strong>Aswin B S</strong> - The scientific guy who makes real inventions from imagination. A passionate innovator turning ideas to reality through science and invention.</p>
  </section>

  <section id="links">
    <h2>Connect & Learn More</h2>
    <p><strong>Official Website:</strong> <a href="https://shermodz.blogspot.com" target="_blank" rel="noopener">shermodz.blogspot.com</a></p>
    <p><strong>WhatsApp Channel:</strong> <a href="https://whatsapp.com/channel/0029VbB594THgZWaplNfWj2L" target="_blank" rel="noopener">Join WhatsApp Channel</a></p>
    <p><strong>Arattai Channel:</strong> <a href="https://aratt.ai/@shermodz" target="_blank" rel="noopener">https://aratt.ai/@shermodz</a></p>
    <p><strong>ORCID:</strong> <a href="https://orcid.org/0009-0000-4201-8418" target="_blank" rel="noopener">https://orcid.org/0009-0000-4201-8418</a></p>
    <p><strong>YouTube Channel:</strong> <a href="https://youtube.com/@shermodz" target="_blank" rel="noopener">SHERMODZ on YouTube</a></p>
  </section>

</main>

<footer>
  <p>© 2025 SHERMODZ Community. All Rights Reserved.</p>
</footer>

<script>
  const quizData = [
    {
      question: "Who formulated the laws of motion?",
      choices: ["Albert Einstein", "Isaac Newton", "Nikola Tesla", "Galileo Galilei"],
      answer: 1
    },
    {
      question: "What does E=mc² represent?",
      choices: ["Energy-mass equivalence", "Force equation", "Velocity of light", "Quantum theory"],
      answer: 0
    },
    {
      question: "Which particle is known as the 'God particle'?",
      choices: ["Electron", "Photon", "Higgs Boson", "Proton"],
      answer: 2
    }
  ];

  let currentQuestionIndex = 0;
  const questionEl = document.getElementById('question');
  const choicesEl = document.getElementById('choices');
  const nextBtn = document.getElementById('next-btn');
  const resultEl = document.getElementById('result');

  function loadQuestion() {
    resultEl.textContent = '';
    const currentQuestion = quizData[currentQuestionIndex];
    questionEl.textContent = currentQuestion.question;
    choicesEl.innerHTML = '';
    currentQuestion.choices.forEach((choice, index) => {
      const btn = document.createElement('button');
      btn.textContent = choice;
      btn.style.display = 'block';
      btn.style.margin = '0.4rem 0';
      btn.onclick = () => checkAnswer(index);
      choicesEl.appendChild(btn);
    });
    nextBtn.style.display = 'none';
  }

  function checkAnswer(selected) {
    const currentQuestion = quizData[currentQuestionIndex];
    if(selected === currentQuestion.answer) {
      resultEl.textContent = "Correct!";
      resultEl.style.color = "#4CAF50";
    } else {
      resultEl.textContent = `Wrong! Correct answer: ${currentQuestion.choices[currentQuestion.answer]}`;
      resultEl.style.color = "#f44336";
    }
    Array.from(choicesEl.children).forEach(btn => btn.disabled = true);
    nextBtn.style.display = 'inline-block';
  }

  nextBtn.addEventListener('click', () => {
    currentQuestionIndex++;
    if(currentQuestionIndex < quizData.length) {
      loadQuestion();
    } else {
      questionEl.textContent = "Quiz Completed! Thanks for participating.";
      choicesEl.innerHTML = '';
      nextBtn.style.display = 'none';
      resultEl.textContent = '';
    }
  });

  loadQuestion();

</script>

</body>
</html>    margin:0;
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
  <!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>SHERMODZ — Learning Hub with Media</title>
<meta name="description" content="SHERMODZ learning portal with images and videos for each lesson" />
<link rel="preconnect" href="https://www.youtube.com" crossorigin>
<style>
  :root{
    --bg:#070913; --panel:#0f1724; --muted:#9bb0d1;
    --accent1:#6ee7ff; --accent2:#8b6bff; --glass:rgba(255,255,255,0.03);
    --card-radius:14px; --maxw:1100px; font-family:Inter,system-ui,Roboto,Arial,sans-serif;
  }
  *{box-sizing:border-box} body{margin:0;background:
    radial-gradient(600px 300px at 10% 10%, rgba(139,107,255,0.06), transparent 6%),
    linear-gradient(180deg,#06101a 0%, #071224 100%); color:#e8f6ff; line-height:1.45}
  main{max-width:var(--maxw);margin:28px auto;padding:18px}
  header{display:flex;gap:12px;align-items:center;margin-bottom:18px}
  h1{margin:0;font-size:20px}
  .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
  @media(max-width:980px){.grid{grid-template-columns:repeat(2,1fr)}}
  @media(max-width:640px){.grid{grid-template-columns:1fr}}

  .lesson{background:linear-gradient(180deg,rgba(255,255,255,0.01),transparent);padding:14px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}
  .lesson h3{margin:0 0 8px 0}
  .media-row{display:flex;gap:10px;flex-wrap:wrap;align-items:flex-start}
  .thumb{width:100%;max-width:280px;border-radius:10px;overflow:hidden;border:1px solid rgba(255,255,255,0.04);background:#071225}
  .thumb img{width:100%;height:180px;object-fit:cover;display:block}
  .caption{font-size:13px;color:var(--muted);margin-top:8px}
  .video-embed{width:100%;max-width:520px;border-radius:10px;overflow:hidden;border:1px solid rgba(255,255,255,0.03)}
  .video-embed iframe, .video-embed video{width:100%;height:300px;display:block;border:0;background:#000}

  .meta{display:flex;gap:8px;flex-wrap:wrap;margin-top:10px}
  .tag{font-size:12px;color:var(--muted);padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.02);border:1px solid rgba(255,255,255,0.02)}

  /* gallery grid */
  .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:12px}
  @media(max-width:900px){.gallery{grid-template-columns:repeat(2,1fr)}}
  .gallery img{width:100%;height:130px;object-fit:cover;border-radius:8px;cursor:pointer;border:1px solid rgba(255,255,255,0.03)}

  /* lightbox */
  .lightbox{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(2,6,23,0.78);z-index:1200;padding:20px}
  .lightbox.show{display:flex}
  .lightbox-content{max-width:1100px;width:100%;max-height:90vh;overflow:auto;border-radius:12px;background:linear-gradient(180deg,#061026 0%,#081026 100%);padding:12px;border:1px solid rgba(255,255,255,0.04)}
  .lightbox img{max-width:100%;height:auto;border-radius:8px;display:block}
  .close-btn{position:absolute;top:18px;right:22px;background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted);padding:8px 10px;border-radius:8px;cursor:pointer}

  /* download / source row */
  .row{display:flex;gap:8px;align-items:center;margin-top:10px;flex-wrap:wrap}
  .link{background:linear-gradient(90deg,var(--accent1),var(--accent2));color:#021025;padding:8px 12px;border-radius:10px;text-decoration:none;font-weight:700}
  .soft{background:rgba(255,255,255,0.02);color:var(--muted);padding:8px 10px;border-radius:10px;border:1px solid rgba(255,255,255,0.03);text-decoration:none}

  /* accessible note */
  .note{font-size:13px;color:var(--muted);margin-top:10px}
</style>
</head>
<body>
<main>
  <header>
    <div>
      <h1>SHERMODZ Learning Hub — Media-enabled Lessons</h1>
      <div style="color:var(--muted);font-size:13px;margin-top:6px">Every lesson contains images, videos, captions, downloadable media, and an interactive gallery.</div>
    </div>
  </header>

  <!-- Lessons grid: duplicate lesson blocks for each subject and fill media -->
  <section class="grid" id="lessons">

    <!-- Lesson example: Classical Physics -->
    <article class="lesson" data-subject="Classical Physics" id="lesson-classical">
      <h3>Classical Physics — Mechanics & Waves</h3>
      <div class="media-row">
        <figure class="thumb" aria-label="Projectile motion image">
          <img loading="lazy" src="PLACEHOLDER_IMAGE_PROJECTILE.jpg" alt="Projectile motion demonstration with trajectory overlay">
          <figcaption class="caption">Projectile motion: trajectory with air resistance removed</figcaption>
        </figure>

        <div class="video-embed" aria-label="Pendulum simulation video">
          <!-- Replace with direct mp4 or YouTube embed -->
          <iframe loading="lazy" src="https://www.youtube.com/embed/VIDEO_ID_CLASSICAL" title="Pendulum simulation" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          <div class="caption">Pendulum simulation and energy exchange demo</div>
        </div>
      </div>

      <div class="gallery" aria-hidden="false">
        <img loading="lazy" src="PLACEHOLDER_IMAGE_WAVE1.jpg" alt="Harmonic wave snapshot" data-full="PLACEHOLDER_IMAGE_WAVE1_LARGE.jpg">
        <img loading="lazy" src="PLACEHOLDER_IMAGE_WAVE2.jpg" alt="Standing waves in a string" data-full="PLACEHOLDER_IMAGE_WAVE2_LARGE.jpg">
        <img loading="lazy" src="PLACEHOLDER_IMAGE_PENDULUM.jpg" alt="Pendulum motion frames" data-full="PLACEHOLDER_IMAGE_PENDULUM_LARGE.jpg">
      </div>

      <div class="meta">
        <span class="tag">Equations: F=ma, KE=1/2mv^2</span>
        <span class="tag">Level: Beginner → Advanced</span>
        <a class="link" href="DOWNLOADS/classical-notes.pdf" download>Download notes</a>
        <a class="soft" href="#lesson-classical">Open lesson</a>
      </div>
    </article>

    <!-- Lesson example: Quantum Mechanics -->
    <article class="lesson" data-subject="Quantum Mechanics" id="lesson-quantum">
      <h3>Quantum Mechanics — Wavefunctions & Spectra</h3>
      <div class="media-row">
        <figure class="thumb" aria-label="Hydrogen spectrum image">
          <img loading="lazy" src="PLACEHOLDER_IMAGE_HYDROGEN.jpg" alt="Hydrogen emission lines">
          <figcaption class="caption">Hydrogen spectral lines and energy levels</figcaption>
        </figure>

        <div class="video-embed" aria-label="Double-slit demo">
          <video controls preload="metadata" poster="PLACEHOLDER_VIDEO_THUMB_QM.jpg">
            <source src="PLACEHOLDER_VIDEO_DOUBLE_SLIT.mp4" type="video/mp4">
            Your browser does not support the video element.
          </video>
          <div class="caption">Double-slit interference experiment simulation</div>
        </div>
      </div>

      <div class="gallery">
        <img loading="lazy" src="PLACEHOLDER_QM1.jpg" alt="Wavefunction probability plot" data-full="PLACEHOLDER_QM1_LG.jpg">
        <img loading="lazy" src="PLACEHOLDER_QM2.jpg" alt="Quantum tunneling illustration" data-full="PLACEHOLDER_QM2_LG.jpg">
        <img loading="lazy" src="PLACEHOLDER_QM3.jpg" alt="Stern-Gerlach setup" data-full="PLACEHOLDER_QM3_LG.jpg">
      </div>

      <div class="meta">
        <span class="tag">Equations: Schrödinger equation, operators</span>
        <span class="tag">Level: Intermediate → Research</span>
        <a class="link" href="DOWNLOADS/quantum-guide.pdf" download>Download guide</a>
      </div>
    </article>

    <!-- Lesson example: Materials & Nanotech -->
    <article class="lesson" data-subject="Materials" id="lesson-materials">
      <h3>Materials — Graphene & Carbon Nanotubes</h3>
      <div class="media-row">
        <figure class="thumb" aria-label="Graphene microscope image">
          <img loading="lazy" src="PLACEHOLDER_GRAPHENE.jpg" alt="Microscope image of graphene flakes">
          <figcaption class="caption">Graphene flakes on substrate with contrast-enhanced imaging</figcaption>
        </figure>

        <div class="video-embed" aria-label="CNT synthesis video">
          <iframe loading="lazy" src="https://www.youtube.com/embed/VIDEO_ID_MATERIALS" title="CNT synthesis" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          <div class="caption">Carbon nanotube synthesis overview and characterization</div>
        </div>
      </div>

      <div class="gallery">
        <img loading="lazy" src="PLACEHOLDER_CNT1.jpg" alt="Single-wall CNT TEM" data-full="PLACEHOLDER_CNT1_LG.jpg">
        <img loading="lazy" src="PLACEHOLDER_GRAPHENE2.jpg" alt="Graphene lattice image" data-full="PLACEHOLDER_GRAPHENE2_LG.jpg">
        <img loading="lazy" src="PLACEHOLDER_DEVICE.jpg" alt="Graphene-based device" data-full="PLACEHOLDER_DEVICE_LG.jpg">
      </div>

      <div class="meta">
        <span class="tag">Topics: Lattice, synthesis, properties</span>
        <a class="link" href="DOWNLOADS/materials-notes.pdf" download>Download notes</a>
      </div>
    </article>

    <!-- Add more lesson blocks following the same pattern for Relativity, Engineering, Electronics, Psychology, AI, Fictional Tech -->
  </section>

  <div class="note">All lesson images use lazy loading. Click gallery images to open a high-resolution preview. Replace PLACEHOLDER_* URLs with your hosted images and videos. Use descriptive alt text for accessibility.</div>
</main>

<!-- Lightbox for viewing full images and videos -->
<div id="lightbox" class="lightbox" role="dialog" aria-modal="true" aria-hidden="true">
  <button id="closeLightbox" class="close-btn" aria-label="Close">Close</button>
  <div class="lightbox-content" id="lightboxContent" tabindex="0"></div>
</div>

<script>
  // Lightbox: open image or video from data-full or src
  (function(){
    const lb = document.getElementById('lightbox');
    const content = document.getElementById('lightboxContent');
    const closeBtn = document.getElementById('closeLightbox');

    function openLightbox(type, src, alt=''){
      content.innerHTML = '';
      if(type==='image'){
        const img = document.createElement('img'); img.src = src; img.alt = alt || '';
        content.appendChild(img);
      } else if(type==='video'){
        const vid = document.createElement('video'); vid.controls = true; vid.autoplay = true;
        vid.src = src; vid.style.maxWidth='100%'; vid.style.height='auto';
        content.appendChild(vid);
      } else if(type==='iframe'){
        const iframe = document.createElement('iframe'); iframe.src = src; iframe.width='100%'; iframe.height='560';
        iframe.setAttribute('allow','accelerometer; encrypted-media; gyroscope; picture-in-picture'); iframe.allowFullscreen = true;
        content.appendChild(iframe);
      }
      lb.classList.add('show'); lb.setAttribute('aria-hidden','false'); content.focus();
    }

    // open images from gallery
    document.querySelectorAll('.gallery img').forEach(img=>{
      img.addEventListener('click', ()=>{
        const full = img.dataset.full || img.src;
        openLightbox('image', full, img.alt);
      });
    });

    // open video posters or video elements
    document.querySelectorAll('.video-embed iframe').forEach(ifr=>{
      // clicking the embed container opens iframe in lightbox for a cleaner view on mobile
      ifr.closest('.video-embed').addEventListener('click', (e)=>{
        const src = ifr.src;
        openLightbox('iframe', src);
        e.stopPropagation();
      });
    });

    document.querySelectorAll('.video-embed video').forEach(v=>{
      v.addEventListener('click', (e)=>{
        const src = v.querySelector('source')?.src || v.currentSrc;
        openLightbox('video', src);
        e.stopPropagation();
      });
    });

    closeBtn.addEventListener('click', ()=>{ lb.classList.remove('show'); lb.setAttribute('aria-hidden','true'); });
    lb.addEventListener('click', (e)=>{ if(e.target===lb) { lb.classList.remove('show'); lb.setAttribute('aria-hidden','true'); } });
    window.addEventListener('keydown', e=>{ if(e.key==='Escape'){ lb.classList.remove('show'); lb.setAttribute('aria-hidden','true'); } });

  })();

  // Accessibility: ensure video iframes use title and loading
  document.querySelectorAll('iframe').forEach((f,i)=>{ if(!f.title) f.title = 'Embedded media frame ' + (i+1); if(!f.loading) f.loading='lazy'; });

  // Guidance helper for maintainers: auto-convert YouTube share links to embeddable format if pasted
  // Not interactive here, just placeholder behavior explanation for manual use.
</script>
</body>
</html>
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>SHERMODZ — Learning Hub</title>
<meta name="description" content="SHERMODZ — science community: multi-topic lessons with images, videos, quizzes and animations." />
<style>
  /* ---- Theme / Basic ---- */
  :root{
    --bg:#050614;
    --card:#0e1630;
    --muted:#99b0d1;
    --accent1:#6ee7ff;
    --accent2:#8b6bff;
    --accent3:#ff6ec7;
    --glass: rgba(255,255,255,0.03);
    --radius:14px;
    --maxw:1100px;
    --ease:cubic-bezier(.2,.9,.3,1);
    font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
    color-scheme: dark;
  }
  *{box-sizing:border-box}
  html,body{height:100%;margin:0;background:
    radial-gradient(700px 300px at 10% 8%, rgba(139,107,255,0.05), transparent 6%),
    linear-gradient(180deg,#03040a 0%, #071226 100%);}
  body{color:#e8f7ff; -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale; line-height:1.45;}
  a{color:var(--accent1); text-decoration:none}
  main{max-width:var(--maxw); margin:20px auto; padding:16px}

  /* ---- Header ---- */
  header{display:flex;gap:16px;align-items:center;padding:12px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);border:1px solid rgba(255,255,255,0.03);backdrop-filter: blur(6px)}
  .logo-wrap{display:flex;align-items:center;gap:12px}
  .logo {
    width:64px;height:64px;border-radius:14px;padding:6px;background:conic-gradient(from 200deg,#6ee7ff,#8b6bff,#ff6ec7);display:flex;align-items:center;justify-content:center;flex-shrink:0;box-shadow:0 8px 30px rgba(99,102,241,0.08);
  }
  .logo img{width:100%;height:100%;object-fit:cover;border-radius:10px;border:3px solid rgba(2,6,23,0.6)}
  .brand-title{font-weight:800;letter-spacing:0.6px}
  nav{margin-left:auto;display:flex;gap:8px;align-items:center;flex-wrap:wrap}
  .nav-link{padding:8px 12px;border-radius:10px;font-weight:700;font-size:13px;color:var(--muted);background:transparent;border:1px solid rgba(255,255,255,0.02);transition:all .25s var(--ease)}
  .nav-link.active{background:linear-gradient(90deg,var(--accent1),var(--accent2));color:#031025;box-shadow:0 8px 30px rgba(99,102,241,0.08)}
  .nav-link:hover{transform:translateY(-3px);box-shadow:0 12px 30px rgba(6,8,20,0.6);color:#eaf8ff}

  /* ---- Hero ---- */
  .hero{display:grid;grid-template-columns:1fr 360px;gap:18px;align-items:center;margin-top:18px}
  .hero-card{padding:18px;border-radius:16px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);border:1px solid rgba(255,255,255,0.03)}
  .hero h1{margin:0;font-size:22px}
  .motto{color:var(--muted);margin-top:8px}
  .cta{display:flex;gap:10px;margin-top:12px}
  .btn{padding:10px 14px;border-radius:12px;font-weight:800;border:0;cursor:pointer}
  .btn-primary{background:linear-gradient(90deg,var(--accent1),var(--accent2));color:#031025}
  .btn-ghost{background:transparent;border:1px solid rgba(255,255,255,0.04);color:var(--muted)}

  /* ---- Layout / Cards ---- */
  .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:16px}
  @media(max-width:980px){ .hero{grid-template-columns:1fr} .grid{grid-template-columns:repeat(2,1fr)} nav{display:none} }
  @media(max-width:640px){ .grid{grid-template-columns:1fr} header{flex-direction:column;align-items:flex-start} .logo{width:56px;height:56px} }

  .topic-card{padding:14px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);border:1px solid rgba(255,255,255,0.03);transition:transform .28s var(--ease), box-shadow .28s var(--ease)}
  .topic-card:hover{transform:translateY(-8px);box-shadow:0 30px 60px rgba(2,6,23,0.6)}
  .topic-card h3{margin:0 0 8px 0}
  .topic-card p{color:var(--muted);margin:0;font-size:13px}

  /* ---- Animated icons ---- */
  .icon-dot{width:10px;height:10px;border-radius:50%;background:var(--accent1);box-shadow:0 6px 20px rgba(110,231,255,0.12);display:inline-block;margin-right:8px}
  .pulse{animation:pulse 2s infinite}
  @keyframes pulse{0%{transform:scale(1)}50%{transform:scale(1.18)}100%{transform:scale(1)}}

  /* ---- Content area (SPA pages) ---- */
  .page{display:none;opacity:0;transform:translateY(8px);transition:opacity .36s var(--ease), transform .36s var(--ease)}
  .page.active{display:block;opacity:1;transform:translateY(0)}
  .page .card{padding:14px;border-radius:12px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);border:1px solid rgba(255,255,255,0.03);}

  /* ---- Media gallery ---- */
  .media{display:flex;gap:12px;flex-wrap:wrap;margin-top:12px}
  .media .thumb{width:100%;max-width:300px;border-radius:10px;overflow:hidden;border:1px solid rgba(255,255,255,0.03);background:#07101a}
  .media img{width:100%;height:180px;object-fit:cover;display:block}
  .video-wrap{flex:1;min-width:260px;border-radius:10px;overflow:hidden;border:1px solid rgba(255,255,255,0.03)}
  .video-wrap iframe, .video-wrap video{width:100%;height:260px;border:0;display:block}

  /* ---- Lightbox ---- */
  .lightbox{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(2,6,23,0.8);z-index:1200;padding:18px}
  .lightbox.show{display:flex}
  .lb-body{max-width:1100px;width:100%;max-height:90vh;overflow:auto;border-radius:12px;background:#061026;padding:12px;border:1px solid rgba(255,255,255,0.03)}
  .lb-body img, .lb-body video, .lb-body iframe{width:100%;height:auto;border-radius:8px;display:block}
  .lb-close{position:absolute;top:16px;right:18px;padding:8px 10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:var(--muted);cursor:pointer}

  /* ---- Footer ---- */
  footer{margin:28px auto;text-align:center;color:var(--muted);font-size:13px}

  /* ---- Utilities ---- */
  .row{display:flex;gap:8px;align-items:center;flex-wrap:wrap}
  .tag{font-size:12px;color:var(--muted);padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.02)}
  .hidden{display:none}
</style>
</head>
<body>
<header>
  <div class="logo-wrap">
    <div class="logo" aria-hidden="true">
      <!-- add your circular profile image here (replace src) -->
      <img id="profileImg" src="PLACEHOLDER_PFP.jpg" alt="SHERMODZ Resources profile">
    </div>
    <div>
      <div class="brand-title">SHERMODZ</div>
      <div style="font-size:12px;color:var(--muted)">Imagination → Science → Invention • Founder: Aswin B S</div>
    </div>
  </div>

  <nav id="mainNav" aria-label="Main navigation">
    <button class="nav-link active" data-route="">Home</button>
    <button class="nav-link" data-route="classical">Classical</button>
    <button class="nav-link" data-route="theory">Theoretical</button>
    <button class="nav-link" data-route="quantum">Quantum</button>
    <button class="nav-link" data-route="relativity">Relativity</button>
    <button class="nav-link" data-route="materials">Materials</button>
    <button class="nav-link" data-route="electronics">Electronics</button>
    <button class="nav-link" data-route="ai">AI</button>
  </nav>
</header>

<main>
  <section class="hero">
    <div class="hero-card">
      <h1>SHERMODZ — Learn, Experiment, Invent</h1>
      <div class="motto">Science is not a subject, it is a way to see and invent the world</div>
      <div class="cta">
        <button class="btn btn-primary" id="exploreBtn">Explore Topics</button>
        <a class="btn btn-ghost" href="https://shermodz.blogspot.com" target="_blank" rel="noopener">Visit Blog</a>
      </div>

      <div style="margin-top:12px" class="row">
        <div class="icon-dot pulse" aria-hidden="true"></div>
        <div style="color:var(--muted);font-size:13px">Interactive lessons with images, videos, quizzes and downloadable notes</div>
      </div>
    </div>

    <aside class="topic-card">
      <div style="display:flex;flex-direction:column;gap:10px">
        <div><strong style="color:var(--accent1)">Quick links</strong></div>
        <div class="row">
          <a class="tag" href="#/classical">Classical</a>
          <a class="tag" href="#/quantum">Quantum</a>
          <a class="tag" href="#/relativity">Relativity</a>
          <a class="tag" href="#/materials">Materials</a>
        </div>
        <div style="color:var(--muted);font-size:13px">Replace placeholder assets with your images/videos in the code below.</div>
      </div>
    </aside>
  </section>

  <!-- ---- SPA Pages ---- -->
  <section id="pages" style="margin-top:18px">
    <!-- Home page -->
    <div class="page active" id="page-home">
      <div class="card">
        <h2>Welcome to SHERMODZ</h2>
        <p style="color:var(--muted)">A community for sharing scientific knowledge, new technologies discovered by SHERMODZ, and practical experiments that turn imagination into invention.</p>
        <div class="grid" style="margin-top:14px">
          <!-- summary topic cards -->
          <article class="topic-card" role="button" tabindex="0" data-route="classical">
            <h3>Classical Physics</h3>
            <p>Newtonian mechanics, waves, thermodynamics, electromagnetism — equations and demos.</p>
          </article>
          <article class="topic-card" role="button" tabindex="0" data-route="theory">
            <h3>Theoretical Physics</h3>
            <p>Lagrangians, field theory, symmetry, and the mathematical language of physics.</p>
          </article>
          <article class="topic-card" role="button" tabindex="0" data-route="quantum">
            <h3>Quantum Mechanics</h3>
            <p>Wavefunctions, operators, spectra, entanglement and hydrogen lines.</p>
          </article>
          <article class="topic-card" role="button" tabindex="0" data-route="relativity">
            <h3>Relativity</h3>
            <p>Special and general relativity, spacetime, metrics, and gravitational waves.</p>
          </article>
          <article class="topic-card" role="button" tabindex="0" data-route="materials">
            <h3>Materials & Nanotech</h3>
            <p>Graphene, carbon nanotubes, lattice structures and device integration.</p>
          </article>
          <article class="topic-card" role="button" tabindex="0" data-route="electronics">
            <h3>Electronics</h3>
            <p>AC/DC, polyphase motors, circuits, sensors, and instrumentation.</p>
          </article>
          <article class="topic-card" role="button" tabindex="0" data-route="ai">
            <h3>AI & Computation</h3>
            <p>ML workflows, simulations, scientific computing and data-driven experiments.</p>
          </article>
        </div>
      </div>
    </div>

    <!-- Topic template (reused) -->
    <template id="topic-template">
      <div class="page" id="">
        <div class="card">
          <div style="display:flex;justify-content:space-between;align-items:center;gap:12px">
            <div>
              <h2 class="topic-title">Topic</h2>
              <div style="color:var(--muted)" class="topic-desc">Short topic description...</div>
            </div>
            <div class="row">
              <a class="tag" href="#" id="download-notes">Download notes</a>
              <a class="tag" href="#" id="open-quiz">Open quiz</a>
            </div>
          </div>

          <div class="media" style="margin-top:12px">
            <figure class="thumb">
              <img loading="lazy" src="PLACEHOLDER_IMAGE1.jpg" alt="Lesson image 1" />
              <figcaption class="caption" style="color:var(--muted);font-size:13px">Sample image 1</figcaption>
            </figure>

            <div class="video-wrap">
              <!-- use either video tag (mp4) or iframe for YouTube -->
              <iframe loading="lazy" src="https://www.youtube.com/embed/PLACEHOLDER_VIDEO_ID" title="Lesson Video" allow="accelerometer; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
              <div class="caption" style="color:var(--muted);font-size:13px">Sample demonstration video</div>
            </div>
          </div>

          <div class="gallery" style="margin-top:12px;display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:8px">
            <img loading="lazy" src="PLACEHOLDER_IMAGE_G1.jpg" alt="Gallery 1" data-full="PLACEHOLDER_IMAGE_G1_LG.jpg">
            <img loading="lazy" src="PLACEHOLDER_IMAGE_G2.jpg" alt="Gallery 2" data-full="PLACEHOLDER_IMAGE_G2_LG.jpg">
            <img loading="lazy" src="PLACEHOLDER_IMAGE_G3.jpg" alt="Gallery 3" data-full="PLACEHOLDER_IMAGE_G3_LG.jpg">
          </div>

          <div style="margin-top:12px;color:var(--muted)">
            <h4 style="margin:0 0 6px 0">Key equations & notes</h4>
            <pre style="background:rgba(255,255,255,0.02);padding:10px;border-radius:8px;overflow:auto;color:#dfeeff">/* Add equations, code, references here */</pre>
          </div>
        </div>
      </div>
    </template>

    <!-- Pre-generate pages for each topic (IDs must match nav data-route values) -->
    <div id="topic-pages"></div>

  </section>

  <!-- Lightbox for images / videos -->
  <div id="lightbox" class="lightbox" role="dialog" aria-modal="true" aria-hidden="true">
    <button class="lb-close" id="lbClose">Close</button>
    <div class="lb-body" id="lbBody" tabindex="0"></div>
  </div>

  <footer>
    <div>SHERMODZ — Imagination is more important than knowledge. Founder: Aswin B S</div>
    <div style="margin-top:8px;color:var(--muted)">shermodz.blogspot.com • <a href="https://youtube.com/@shermodz" target="_blank">YouTube</a> • <a href="https://whatsapp.com/channel/0029VbB594THgZWaplNfWj2L" target="_blank">WhatsApp</a></div>
  </footer>
</main>

<script>
  /* ---- Data: topics with placeholders. Replace asset URLs with your real ones ---- */
  const TOPICS = {
    classical: {
      id:'classical', title:'Classical Physics', desc:'Newtonian mechanics, waves, thermodynamics and electromagnetism.',
      heroImg:'PLACEHOLDER_CLASSICAL_BIG.jpg',
      videoEmbed:'https://www.youtube.com/embed/PLACEHOLDER_VIDEO_ID_CLASSICAL',
      gallery:['PLACEHOLDER_CLASSICAL_G1.jpg','PLACEHOLDER_CLASSICAL_G2.jpg','PLACEHOLDER_CLASSICAL_G3.jpg'],
      notes:'DOWNLOADS/classical-notes.pdf'
    },
    theory: {
      id:'theory', title:'Theoretical Physics', desc:'Lagrangians, Hamiltonians, symmetry, and field theory.',
      heroImg:'PLACEHOLDER_THEORY_BIG.jpg', videoEmbed:'https://www.youtube.com/embed/PLACEHOLDER_VIDEO_ID_THEORY',
      gallery:['PLACEHOLDER_THEORY_G1.jpg','PLACEHOLDER_THEORY_G2.jpg','PLACEHOLDER_THEORY_G3.jpg'],
      notes:'DOWNLOADS/theory-notes.pdf'
    },
    quantum: {
      id:'quantum', title:'Quantum Mechanics', desc:'Schrödinger equation, spectra, entanglement and experiments.',
      heroImg:'PLACEHOLDER_QUANTUM_BIG.jpg', videoEmbed:'https://www.youtube.com/embed/PLACEHOLDER_VIDEO_ID_QUANTUM',
      gallery:['PLACEHOLDER_QUANTUM_G1.jpg','PLACEHOLDER_QUANTUM_G2.jpg','PLACEHOLDER_QUANTUM_G3.jpg'],
      notes:'DOWNLOADS/quantum-notes.pdf'
    },
    relativity: {
      id:'relativity', title:'Relativity', desc:'Special and general relativity, spacetime geometry and gravitational waves.',
      heroImg:'PLACEHOLDER_REL_BIG.jpg', videoEmbed:'https://www.youtube.com/embed/PLACEHOLDER_VIDEO_ID_REL',
      gallery:['PLACEHOLDER_REL_G1.jpg','PLACEHOLDER_REL_G2.jpg','PLACEHOLDER_REL_G3.jpg'],
      notes:'DOWNLOADS/relativity-notes.pdf'
    },
    materials: {
      id:'materials', title:'Materials & Nanotech', desc:'Graphene, CNTs, synthesis and device integration.',
      heroImg:'PLACEHOLDER_MAT_BIG.jpg', videoEmbed:'https://www.youtube.com/embed/PLACEHOLDER_VIDEO_ID_MAT',
      gallery:['PLACEHOLDER_MAT_G1.jpg','PLACEHOLDER_MAT_G2.jpg','PLACEHOLDER_MAT_G3.jpg'],
      notes:'DOWNLOADS/materials-notes.pdf'
    },
    electronics: {
      id:'electronics', title:'Electronics', desc:'Circuits, AC/DC, motors, sensors, and instrumentation.',
      heroImg:'PLACEHOLDER_ELEC_BIG.jpg', videoEmbed:'https://www.youtube.com/embed/PLACEHOLDER_VIDEO_ID_ELEC',
      gallery:['PLACEHOLDER_ELEC_G1.jpg','PLACEHOLDER_ELEC_G2.jpg','PLACEHOLDER_ELEC_G3.jpg'],
      notes:'DOWNLOADS/electronics-notes.pdf'
    },
    ai: {
      id:'ai', title:'AI & Computation', desc:'Machine learning, simulations, and data-driven science.',
      heroImg:'PLACEHOLDER_AI_BIG.jpg', videoEmbed:'https://www.youtube.com/embed/PLACEHOLDER_VIDEO_ID_AI',
      gallery:['PLACEHOLDER_AI_G1.jpg','PLACEHOLDER_AI_G2.jpg','PLACEHOLDER_AI_G3.jpg'],
      notes:'DOWNLOADS/ai-notes.pdf'
    }
  };

  /* ---- Initialize: build topic pages from template ---- */
  (function buildPages(){
    const container = document.getElementById('topic-pages');
    const tpl = document.getElementById('topic-template');
    Object.values(TOPICS).forEach(topic=>{
      const clone = tpl.content.cloneNode(true);
      const page = clone.querySelector('.page');
      page.id = 'page-'+topic.id;
      page.querySelector('.topic-title').textContent = topic.title;
      page.querySelector('.topic-desc').textContent = topic.desc;
      page.querySelector('img.thumb img')?.setAttribute('src', topic.heroImg);
      // set iframe video
      const iframe = page.querySelector('iframe');
      if(iframe) iframe.src = topic.videoEmbed;
      // gallery images
      const imgs = page.querySelectorAll('.gallery img');
      imgs.forEach((img,i)=>{
        img.src = topic.gallery[i] || topic.gallery[0] || 'PLACEHOLDER_GENERIC.jpg';
        img.dataset.full = topic.gallery[i] || img.src;
      });
      // notes link
      const dl = page.querySelector('#download-notes');
      if(dl) { dl.href = topic.notes; dl.setAttribute('download',''); }
      container.appendChild(clone);
    });
  })();

  /* ---- Simple hash routing ---- */
  (function routing(){
    const navBtns = document.querySelectorAll('.nav-link');
    function setActiveRoute(route){
      // highlight nav
      navBtns.forEach(b=> b.classList.toggle('active', b.dataset.route===route || (route==='' && b.dataset.route==='')));
      // show page
      document.querySelectorAll('.page').forEach(p=> p.classList.remove('active'));
      if(!route || !TOPICS[route]){
        document.getElementById('page-home').classList.add('active');
        history.replaceState(null,'', '#/');
        return;
      }
      const el = document.getElementById('page-'+route);
      if(el){ el.classList.add('active'); history.replaceState(null,'', '#/'+route); }
    }
    // nav click
    navBtns.forEach(b=>{
      b.addEventListener('click', ()=> setActiveRoute(b.dataset.route || ''));
    });
    // cards clickable
    document.querySelectorAll('.topic-card').forEach(c=>{
      c.addEventListener('click', ()=> setActiveRoute(c.dataset.route));
      c.addEventListener('keypress', e=>{ if(e.key==='Enter') setActiveRoute(c.dataset.route); });
    });
    // handle hash changes on load
    function handleHash(){
      const h = location.hash.replace('#/','') || '';
      setActiveRoute(h);
    }
    window.addEventListener('hashchange', handleHash);
    handleHash();
  })();

  /* ---- Lightbox ---- */
  (function lightbox(){
    const lb = document.getElementById('lightbox');
    const lbBody = document.getElementById('lbBody');
    const lbClose = document.getElementById('lbClose');
    // open on gallery image click
    document.addEventListener('click', e=>{
      const img = e.target.closest('.gallery img, .media img, .thumb img');
      if(img){
        const src = img.dataset.full || img.src;
        lbBody.innerHTML = '';
        const large = document.createElement('img');
        large.src = src;
        large.alt = img.alt || '';
        lbBody.appendChild(large);
        lb.classList.add('show'); lb.setAttribute('aria-hidden','false');
      }
      // video iframe click: open in lightbox as iframe
      const iframeWrap = e.target.closest('.video-wrap iframe');
      if(iframeWrap){
        const src = iframeWrap.src;
        lbBody.innerHTML = '';
