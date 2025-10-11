<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Shermodz — Open Science Community</title>
  <meta name="description" content="Shermodz — community for sharing incredible scientific knowledge and building out-of-the-box thinking." />
  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* small custom styles */
    :root{--accent:#3b82f6}
    .fancy-border{background:linear-gradient(90deg,rgba(59,130,246,0.15),rgba(168,85,247,0.08));border-radius:18px}
  </style>
</head>
<body class="bg-gray-50 text-gray-900 antialiased">
  <!-- Header -->
  <header class="max-w-6xl mx-auto p-6 flex items-center justify-between">
    <a href="https://shermodz.blogspot.com" class="flex items-center gap-3">
      <div class="w-12 h-12 rounded-2xl bg-gradient-to-br from-indigo-500 to-purple-600 flex items-center justify-center text-white font-extrabold">S</div>
      <div>
        <h1 class="text-xl font-semibold">Shermodz</h1>
        <p class="text-xs text-gray-500">Open science • Radical curiosity</p>
      </div>
    </a>
    <nav class="hidden md:flex gap-4 items-center">
      <a href="#about" class="text-sm hover:text-indigo-600">About</a>
      <a href="#topics" class="text-sm hover:text-indigo-600">Topics</a>
      <a href="#contribute" class="text-sm hover:text-indigo-600">Contribute</a>
      <a href="#resources" class="text-sm hover:text-indigo-600">Resources</a>
      <a href="#contact" class="inline-flex items-center gap-2 px-4 py-2 rounded-lg bg-indigo-50 text-indigo-600 text-sm">Join WhatsApp</a>
    </nav>
    <button id="themeToggle" class="md:hidden p-2 bg-gray-100 rounded-lg">☼</button>
  </header>

  <!-- Hero -->
  <section class="max-w-6xl mx-auto px-6 py-12 grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
    <div>
      <h2 class="text-4xl font-extrabold leading-tight">Science is not a subject,<br><span class="text-indigo-600">it is a way to see the world</span></h2>
      <p class="mt-4 text-gray-600">Welcome to Shermodz — a community for sharing incredible scientific knowledge and building out-of-the-box thinking. Discover new technologies and research by Shermodz, ask questions, and collaborate.</p>

      <div class="mt-6 flex gap-3">
        <a href="https://shermodz.blogspot.com" class="px-4 py-2 rounded-lg bg-indigo-600 text-white shadow hover:scale-105 transition">Visit Blog</a>
        <a href="https://youtube.com/@shermodz" class="px-4 py-2 rounded-lg border border-indigo-200 text-indigo-600 hover:bg-indigo-50 transition">YouTube</a>
      </div>

      <div class="mt-6 grid grid-cols-2 gap-3 text-sm text-gray-700">
        <div class="fancy-border p-3">
          <strong>WhatsApp channel</strong>
          <div class="text-xs mt-2 break-words">https://whatsapp.com/channel/0029VbB594THgZWaplNfWj2L</div>
        </div>
        <div class="fancy-border p-3">
          <strong>Arattai</strong>
          <div class="text-xs mt-2 break-words">https://aratt.ai/@shermodz</div>
        </div>
        <div class="fancy-border p-3">
          <strong>ORCID</strong>
          <div class="text-xs mt-2"><a class="text-indigo-600" href="https://orcid.org/0009-0000-4201-8418">0009-0000-4201-8418</a></div>
        </div>
        <div class="fancy-border p-3">
          <strong>Blog</strong>
          <div class="text-xs mt-2"><a class="text-indigo-600" href="https://shermodz.blogspot.com">shermodz.blogspot.com</a></div>
        </div>
      </div>
    </div>

    <div class="bg-white rounded-2xl p-6 shadow-lg">
      <h3 class="text-lg font-semibold">Ask a question — get scientific help</h3>
      <p class="text-sm text-gray-500 mt-2">We can help with classical physics, quantum mechanics, engineering, chemistry, materials, electronics, psychology and turning fictional technology into practical prototypes.</p>

      <form id="questionForm" class="mt-4 grid gap-3">
        <input required name="name" placeholder="Your name" class="p-3 border rounded-lg" />
        <input required name="email" placeholder="Email (optional)" class="p-3 border rounded-lg" />
        <textarea required name="question" placeholder="Describe your scientific question or idea" rows="6" class="p-3 border rounded-lg"></textarea>
        <div class="flex gap-2">
          <button type="submit" class="px-4 py-2 rounded-lg bg-indigo-600 text-white">Submit</button>
          <button type="button" id="copyLinks" class="px-4 py-2 rounded-lg border">Copy Links</button>
        </div>
        <div id="formMsg" class="text-sm text-green-600 hidden">Thanks — your question was prepared. Use mailto to send or paste it in the WhatsApp channel.</div>
      </form>

      <div class="mt-6 text-xs text-gray-500">Tip: Use the WhatsApp channel to share quick updates or the blog for longer writeups.</div>
    </div>
  </section>

  <!-- Topics -->
  <section id="topics" class="max-w-6xl mx-auto px-6 py-12">
    <h3 class="text-2xl font-bold">Topics we cover</h3>
    <p class="text-gray-600 mt-2">Deep dives, tutorials, blueprints and open research.</p>

    <div class="mt-6 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
      <!-- Card template -->
      <article class="p-5 bg-white rounded-2xl shadow-sm">
        <h4 class="font-semibold">Classical & Theoretical Physics</h4>
        <p class="text-sm text-gray-500 mt-1">Mechanics, electromagnetism, field theory and mathematical foundations.</p>
      </article>

      <article class="p-5 bg-white rounded-2xl shadow-sm">
        <h4 class="font-semibold">Quantum Mechanics</h4>
        <p class="text-sm text-gray-500 mt-1">Superposition, entanglement, quantum algorithms and experiments.</p>
      </article>

      <article class="p-5 bg-white rounded-2xl shadow-sm">
        <h4 class="font-semibold">Relativity</h4>
        <p class="text-sm text-gray-500 mt-1">Special & general relativity, spacetime geometry and thought experiments.</p>
      </article>

      <article class="p-5 bg-white rounded-2xl shadow-sm">
        <h4 class="font-semibold">Engineering & Electronics</h4>
        <p class="text-sm text-gray-500 mt-1">Prototyping, circuits, control systems and embedded design.</p>
      </article>

      <article class="p-5 bg-white rounded-2xl shadow-sm">
        <h4 class="font-semibold">Materials & Inorganic Chemistry</h4>
        <p class="text-sm text-gray-500 mt-1">Advanced materials, CVD, nanotubes and practical chemistry safety notes.</p>
      </article>

      <article class="p-5 bg-white rounded-2xl shadow-sm">
        <h4 class="font-semibold">Psychology & Scientific Thinking</h4>
        <p class="text-sm text-gray-500 mt-1">How to reason, design experiments and solve real-world problems with science.</p>
      </article>
    </div>
  </section>

  <!-- Contribute -->
  <section id="contribute" class="max-w-6xl mx-auto px-6 py-12 bg-gradient-to-r from-indigo-50 to-purple-50 rounded-2xl mx-6">
    <div class="grid md:grid-cols-2 gap-6 items-center">
      <div>
        <h3 class="text-2xl font-bold">Open Research & Contribution</h3>
        <p class="text-gray-700 mt-2">We welcome experiments, blueprints, and peer review. Add your work to the blog or submit it for community review.</p>

        <ul class="mt-4 text-sm text-gray-600 space-y-2">
          <li>• Share reproducible experiments and data.</li>
          <li>• Write tutorials and step-by-step build guides.</li>
          <li>• Help others convert fictional ideas into realistic prototypes.</li>
        </ul>

        <div class="mt-4 flex gap-3">
          <a href="https://orcid.org/0009-0000-4201-8418" class="px-4 py-2 rounded-lg bg-white border">ORCID</a>
          <a href="https://youtube.com/@shermodz" class="px-4 py-2 rounded-lg bg-white border">YouTube</a>
        </div>
      </div>

      <div class="bg-white p-5 rounded-2xl shadow-sm">
        <h4 class="font-semibold">How to contribute</h4>
        <ol class="text-sm mt-2 text-gray-600 list-decimal list-inside">
          <li>Draft your article or experiment on the blog.</li>
          <li>Share a link in the WhatsApp channel for feedback.</li>
          <li>Open a GitHub repo for code or designs and link it in your post.</li>
        </ol>

        <div class="mt-4 text-xs text-gray-500">Want, I can give you a starter README and GitHub instructions to publish your site — choose GitHub Pages or Netlify.</div>
      </div>
    </div>
  </section>

  <!-- Resources -->
  <section id="resources" class="max-w-6xl mx-auto px-6 py-12">
    <h3 class="text-2xl font-bold">Useful links & resources</h3>
    <div class="mt-4 grid sm:grid-cols-2 gap-4">
      <a href="https://shermodz.blogspot.com" class="p-4 bg-white rounded-xl shadow-sm flex items-start gap-3">
        <div class="w-10 h-10 rounded-lg bg-indigo-100 flex items-center justify-center">B</div>
        <div>
          <div class="font-semibold">Shermodz Blog</div>
          <div class="text-sm text-gray-500">Long-form posts and blueprints.</div>
        </div>
      </a>

      <a href="https://youtube.com/@shermodz" class="p-4 bg-white rounded-xl shadow-sm flex items-start gap-3">
        <div class="w-10 h-10 rounded-lg bg-red-100 flex items-center justify-center">▶</div>
        <div>
          <div class="font-semibold">YouTube channel</div>
          <div class="text-sm text-gray-500">Videos and demonstrations.</div>
        </div>
      </a>
    </div>
  </section>

  <!-- Footer -->
  <footer id="contact" class="max-w-6xl mx-auto px-6 py-8 text-sm text-gray-600">
    <div class="flex flex-col md:flex-row md:justify-between gap-4">
      <div>
        <div class="font-semibold">Shermodz</div>
        <div>Open research • Community • Tutorials</div>
      </div>
      <div class="flex gap-4">
        <a href="https://whatsapp.com/channel/0029VbB594THgZWaplNfWj2L">WhatsApp Channel</a>
        <a href="https://aratt.ai/@shermodz">Aratt.ai</a>
        <a href="https://orcid.org/0009-0000-4201-8418">ORCID</a>
      </div>
    </div>

    <div class="mt-6 text-gray-500">© Shermodz — Built for curious minds. Proudly open & contributable.</div>
  </footer>

  <script>
    // simple form handler
    document.getElementById('questionForm').addEventListener('submit', function(e){
      e.preventDefault();
      const name = this.name.value || 'Anonymous';
      const email = this.email.value || '';
      const question = this.question.value;
      const subject = encodeURIComponent('Shermodz question from ' + name);
      const body = encodeURIComponent('Name: '+name+"\nEmail: "+email+"\n\n"+question);
      // open user's mail client to send
      window.location.href = 'mailto:shermodz+questions@gmail.com?subject='+subject+'&body='+body;
      document.getElementById('formMsg').classList.remove('hidden');
    });

    // copy links
    document.getElementById('copyLinks').addEventListener('click', function(){
      const text = [
        'Blog: https://shermodz.blogspot.com',
        'WhatsApp: https://whatsapp.com/channel/0029VbB594THgZWaplNfWj2L',
        'YouTube: https://youtube.com/@shermodz',
        'Aratt: https://aratt.ai/@shermodz',
        'ORCID: https://orcid.org/0009-0000-4201-8418'
      ].join('\n');
      navigator.clipboard?.writeText(text).then(()=>alert('Links copied to clipboard'));
    });

    // theme toggle (basic)
    const btn = document.getElementById('themeToggle');
    btn.addEventListener('click', ()=>{
      document.documentElement.classList.toggle('dark');
      document.body.classList.toggle('bg-gray-900');
      document.body.classList.toggle('text-gray-50');
    });
  </script>
</body>
</html>
