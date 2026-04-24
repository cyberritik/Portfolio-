# Portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ritik Goyal | Data Analyst & Data Scientist</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"/>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
    body { font-family: 'Inter', sans-serif; }
    .hero-bg { background: linear-gradient(135deg, #0f0f1e 0%, #1a1433 100%); }
    .glow { text-shadow: 0 0 30px rgba(34, 211, 238, 0.6); }
    section { min-height: 100vh; scroll-margin-top: 80px; }
    .card-hover:hover { transform: translateY(-8px); box-shadow: 0 25px 50px -12px rgb(34 211 238 / 0.3); }
  </style>
</head>
<body class="bg-zinc-950 text-white overflow-x-hidden">

  <!-- Navbar -->
  <nav class="fixed top-0 w-full z-50 bg-zinc-900/90 backdrop-blur-xl border-b border-white/10">
    <div class="max-w-7xl mx-auto px-8 py-6 flex justify-between items-center">
      <div class="text-3xl font-bold tracking-[-2px] glow">RITIK GOYAL</div>
      <div class="flex gap-10 font-medium">
        <a href="#about" class="hover:text-cyan-400 transition-colors">About</a>
        <a href="#experience" class="hover:text-cyan-400 transition-colors">Experience</a>
        <a href="#projects" class="hover:text-cyan-400 transition-colors">Projects</a>
        <a href="#skills" class="hover:text-cyan-400 transition-colors">Skills</a>
        <a href="#contact" class="hover:text-cyan-400 transition-colors">Contact</a>
      </div>
      <a href="YOUR-RESUME-LINK-HERE.pdf" download class="px-8 py-3.5 bg-cyan-400 hover:bg-white text-black font-semibold rounded-3xl flex items-center gap-2">
        <i class="fas fa-download"></i> Download CV
      </a>
    </div>
  </nav>

  <!-- HERO -->
  <section class="hero-bg min-h-screen flex items-center relative pt-20">
    <div class="max-w-7xl mx-auto px-8 grid md:grid-cols-12 gap-12 items-center">
      <div class="md:col-span-7">
        <h1 class="text-7xl md:text-[88px] leading-none font-bold mb-4 glow">RITIK GOYAL</h1>
        <h2 id="typing" class="text-5xl md:text-6xl font-semibold text-cyan-400 mb-8"></h2>
        <p class="text-2xl text-gray-300 max-w-xl">Data Science undergrad who turns messy data into clear business wins.</p>
        
        <div class="flex items-center gap-6 mt-12">
          <a href="#contact" class="px-10 py-6 bg-gradient-to-r from-cyan-400 to-purple-500 text-black font-semibold text-xl rounded-3xl hover:scale-105 transition-all">Let's Connect</a>
          <a href="https://linkedin.com/in/ritik-goyal-13520932b" target="_blank" class="flex items-center gap-4 text-xl font-medium border border-white/30 px-8 py-6 rounded-3xl hover:border-cyan-400 transition-all">
            <i class="fab fa-linkedin"></i> LinkedIn
          </a>
        </div>
      </div>
      <div class="md:col-span-5 flex justify-center">
        <div class="text-8xl">📈</div>
      </div>
    </div>
  </section>

  <!-- PROFESSIONAL SUMMARY (1st) -->
  <section id="about" class="py-32 bg-zinc-900">
    <div class="max-w-7xl mx-auto px-8">
      <h2 class="text-6xl font-bold mb-10">Professional Summary</h2>
      <p class="text-xl leading-relaxed text-gray-300 max-w-3xl">
        Data Science undergraduate with strong hands-on experience in data analysis, predictive modelling, and statistical analysis. Skilled in wrangling large datasets, building machine learning models, and delivering actionable business insights.
      </p>
    </div>
  </section>

  <!-- SUMMARY DASHBOARD (2nd) -->
  <section class="py-20 bg-zinc-950">
    <div class="max-w-7xl mx-auto px-8">
      <h2 class="text-5xl font-bold text-center mb-12">Summary Dashboard</h2>
      <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-6">
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl p-8 text-center">
          <div class="text-5xl mb-4">📊</div>
          <h3 class="text-4xl font-bold text-cyan-400">264K+</h3>
          <p class="text-sm text-gray-400 mt-2">Transactions Analyzed</p>
        </div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl p-8 text-center">
          <div class="text-5xl mb-4">🏠</div>
          <h3 class="text-4xl font-bold text-cyan-400">1</h3>
          <p class="text-sm text-gray-400 mt-2">House Price Model Deployed</p>
        </div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl p-8 text-center">
          <div class="text-5xl mb-4">📉</div>
          <h3 class="text-4xl font-bold text-cyan-400">89%</h3>
          <p class="text-sm text-gray-400 mt-2">Churn Prediction Accuracy</p>
        </div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl p-8 text-center">
          <div class="text-5xl mb-4">👥</div>
          <h3 class="text-4xl font-bold text-cyan-400">3</h3>
          <p class="text-sm text-gray-400 mt-2">Customer Segments Identified</p>
        </div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl p-8 text-center">
          <div class="text-5xl mb-4">✅</div>
          <h3 class="text-4xl font-bold text-cyan-400">98%</h3>
          <p class="text-sm text-gray-400 mt-2">Data Labelling Accuracy</p>
        </div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl p-8 text-center">
          <div class="text-5xl mb-4">📈</div>
          <h3 class="text-4xl font-bold text-cyan-400">5+</h3>
          <p class="text-sm text-gray-400 mt-2">Projects Delivered</p>
        </div>
      </div>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section id="experience" class="py-32 bg-zinc-900">
    <div class="max-w-7xl mx-auto px-8">
      <h2 class="text-6xl font-bold mb-16 text-center">Experience</h2>
      <div class="space-y-16 max-w-4xl mx-auto">
        <div class="card-hover flex flex-col md:flex-row gap-8 bg-white/5 border border-white/10 p-10 rounded-3xl">
          <div class="md:w-52 font-mono text-cyan-400 text-lg">Jul 2025 – Nov 2025</div>
          <div class="flex-1">
            <h3 class="text-3xl font-semibold">Data Science Intern</h3>
            <p class="text-cyan-400 mb-6">Codec Technologies Pvt. Ltd.</p>
            <ul class="space-y-4 text-gray-300">
              <li>• Data preprocessing, feature engineering &amp; EDA</li>
              <li>• Built &amp; evaluated multiple regression ML models</li>
              <li>• Improved performance using R², MAE, RMSE</li>
            </ul>
          </div>
        </div>
        <div class="card-hover flex flex-col md:flex-row gap-8 bg-white/5 border border-white/10 p-10 rounded-3xl">
          <div class="md:w-52 font-mono text-cyan-400 text-lg">Jan 2026</div>
          <div class="flex-1">
            <h3 class="text-3xl font-semibold">Data Analyst – Virtual Experience</h3>
            <p class="text-cyan-400 mb-6">Quantium (Forage)</p>
            <ul class="space-y-4 text-gray-300">
              <li>• Analysed 100,000+ retail transactions</li>
              <li>• Identified 3 high-value customer segments</li>
            </ul>
          </div>
        </div>
        <div class="card-hover flex flex-col md:flex-row gap-8 bg-white/5 border border-white/10 p-10 rounded-3xl">
          <div class="md:w-52 font-mono text-cyan-400 text-lg">Jan 2026</div>
          <div class="flex-1">
            <h3 class="text-3xl font-semibold">Data Labeler – Job Simulation</h3>
            <p class="text-cyan-400 mb-6">Forage</p>
            <ul class="space-y-4 text-gray-300">
              <li>• 98%+ accuracy in high-volume labelling</li>
              <li>• PII compliance for ML pipelines</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS (4 projects) -->
  <section id="projects" class="py-32 bg-zinc-950">
    <div class="max-w-7xl mx-auto px-8">
      <h2 class="text-6xl font-bold mb-16 text-center">Featured Projects</h2>
      <div class="grid md:grid-cols-2 gap-8">
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl p-10">
          <div class="text-7xl mb-8">📊</div>
          <h3 class="text-3xl font-semibold mb-3">Retail Customer Segmentation & Sales Analysis</h3>
          <p class="text-gray-400">264,000+ transactions • Brand trends • Pack-size insights • Customer segmentation models</p>
        </div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl p-10">
          <div class="text-7xl mb-8">🏠</div>
          <h3 class="text-3xl font-semibold mb-3">House Price Prediction Model</h3>
          <p class="text-gray-400">End-to-end regression model • Full EDA • Streamlit deployment</p>
        </div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl p-10">
          <div class="text-7xl mb-8">📉</div>
          <h3 class="text-3xl font-semibold mb-3">Customer Churn Prediction Model</h3>
          <p class="text-gray-400">Built binary classification model • 89% accuracy • Key churn factors identified</p>
        </div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl p-10">
          <div class="text-7xl mb-8">📊</div>
          <h3 class="text-3xl font-semibold mb-3">Sales Dashboard & KPI Analysis</h3>
          <p class="text-gray-400">Interactive sales dashboard using SQL, Python & Power BI • Real-time KPIs & forecasts</p>
        </div>
      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills" class="py-32 bg-zinc-900">
    <div class="max-w-7xl mx-auto px-8">
      <h2 class="text-6xl font-bold mb-16 text-center">Core Skills</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl px-8 py-10 text-center text-xl font-medium">Python • SQL • R</div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl px-8 py-10 text-center text-xl font-medium">Pandas • NumPy • SciPy</div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl px-8 py-10 text-center text-xl font-medium">EDA & Feature Engineering</div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl px-8 py-10 text-center text-xl font-medium">Machine Learning (Regression)</div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl px-8 py-10 text-center text-xl font-medium">Matplotlib Visualisation</div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl px-8 py-10 text-center text-xl font-medium">Statistical Analysis</div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl px-8 py-10 text-center text-xl font-medium">Model Evaluation (R², MAE, RMSE)</div>
        <div class="card-hover bg-white/5 border border-white/10 rounded-3xl px-8 py-10 text-center text-xl font-medium">PostgreSQL</div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="py-32 bg-zinc-950">
    <div class="max-w-7xl mx-auto px-8 grid md:grid-cols-2 gap-16">
      <div>
        <h2 class="text-5xl font-bold mb-8">Education</h2>
        <div class="bg-white/5 border border-white/10 rounded-3xl p-10">
          <h3 class="text-3xl font-semibold">B.Tech Computer Science (AI & Data Science)</h3>
          <p class="text-cyan-400 mt-3">Global Institute of Technology and Management, Gurugram</p>
          <p class="text-gray-400 mt-8">Aug 2024 – Expected Jun 2028 | CGPA: 8.5/10</p>
        </div>
      </div>
      <div>
        <h2 class="text-5xl font-bold mb-8">Let's Connect</h2>
        <a href="mailto:ritikgoyal250@gmail.com" class="flex items-center gap-6 mb-10 hover:text-cyan-400"><i class="fas fa-envelope text-5xl"></i> ritikgoyal250@gmail.com</a>
        <a href="tel:+918307401819" class="flex items-center gap-6 mb-10 hover:text-cyan-400"><i class="fas fa-phone text-5xl"></i> +91-8307401819</a>
        <a href="https://linkedin.com/in/ritik-goyal-13520932b" target="_blank" class="flex items-center gap-6 hover:text-cyan-400"><i class="fab fa-linkedin text-5xl"></i> linkedin.com/in/ritik-goyal-13520932b</a>
      </div>
    </div>
  </section>

  <footer class="py-12 text-center text-gray-400 text-sm border-t border-white/10">
    © 2026 Ritik Goyal • Built to impress clients & recruiters
  </footer>

  <script>
    const text = "Data Analyst | Data Science Intern";
    let index = 0;
    const typingElement = document.getElementById("typing");
    function type() {
      if (index < text.length) {
        typingElement.innerHTML += text.charAt(index);
        index++;
        setTimeout(type, 75);
      }
    }
    window.onload = () => type();
  </script>
</body>
</html>
