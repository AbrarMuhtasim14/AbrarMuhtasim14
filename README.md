<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Abrar Muhtasim | Agentic AI Engineer</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"/>
  <style>
    body {
      background: radial-gradient(circle at center, #0a0a0a 0%, #000000 70%);
      font-family: 'Inter', system-ui, sans-serif;
    }
    .neural-bg {
      background: linear-gradient(45deg, #00ffea10, #7b00ff10, #ff00aa10);
      background-size: 400% 400%;
      animation: gradientShift 25s ease infinite;
    }
    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    .agent-card {
      transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
    }
    .agent-card:hover {
      transform: translateY(-12px) scale(1.03);
      box-shadow: 0 0 40px rgba(123, 0, 255, 0.4);
    }
    .glow-text {
      text-shadow: 0 0 20px rgba(0, 255, 234, 0.6);
    }
    .terminal {
      font-family: 'Courier New', monospace;
      animation: blink 1s step-end infinite;
    }
  </style>
</head>
<body class="text-gray-200 neural-bg min-h-screen">

  <!-- Navbar -->
  <nav class="fixed top-0 w-full bg-black/80 backdrop-blur-md z-50 border-b border-cyan-500/20">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <div class="flex items-center gap-3">
        <span class="text-2xl">🧠</span>
        <h1 class="text-xl font-bold tracking-tight">ABRAR MUHTASIM</h1>
      </div>
      <div class="flex gap-8 text-sm font-medium">
        <a href="#agents" class="hover:text-cyan-400 transition">AGENTS</a>
        <a href="#systems" class="hover:text-cyan-400 transition">SYSTEMS</a>
        <a href="#research" class="hover:text-cyan-400 transition">RESEARCH</a>
        <a href="#connect" class="hover:text-cyan-400 transition">CONNECT</a>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="min-h-screen flex items-center justify-center relative overflow-hidden">
    <div class="absolute inset-0 bg-[radial-gradient(#22d3ee_0.8px,transparent_1px)] [background-size:40px_40px] opacity-10"></div>
    
    <div class="max-w-5xl mx-auto text-center px-6 relative z-10">
      <h2 class="text-cyan-400 text-sm tracking-[4px] mb-4 font-mono">PROTOCOL v0.3.1 • ONLINE</h2>
      <h1 class="text-7xl md:text-8xl font-bold mb-6 glow-text">
        I BUILD<br/>AI THAT<br/><span class="text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 via-purple-500 to-pink-500">THINKS FOR ITSELF</span>
      </h1>
      
      <p class="text-xl text-gray-400 max-w-2xl mx-auto mb-10">
        Agentic AI Engineer • Multi-Agent Systems • Memory Architectures • 
        Tool-Using LLM Systems • Grounded Intelligence
      </p>

      <div class="flex gap-4 justify-center">
        <a href="#systems" 
           class="px-8 py-4 bg-gradient-to-r from-cyan-500 to-purple-600 rounded-xl font-semibold hover:scale-105 transition">
          Explore My Systems →
        </a>
        <a href="https://github.com/AbrarMuhtasim14" target="_blank"
           class="px-8 py-4 border border-cyan-400 rounded-xl hover:bg-cyan-400/10 transition">
          <i class="fab fa-github mr-2"></i> GitHub
        </a>
      </div>

      <div class="mt-16 text-xs text-gray-500 font-mono flex justify-center gap-8">
        <div>● 4 ACTIVE AGENTS</div>
        <div>● 3 PUBLICATIONS</div>
        <div>● 100% CITATION RATE</div>
      </div>
    </div>

    <div class="absolute bottom-10 text-cyan-400 text-sm font-mono flex items-center gap-2">
      <span class="terminal">█</span>
      INITIALIZING AGENTIC CORE...
    </div>
  </section>

  <!-- Agents Section -->
  <section id="agents" class="py-24 border-t border-cyan-500/10">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-16">Autonomous Agents I Deploy</h2>
      
      <div class="grid md:grid-cols-3 gap-8">
        <div class="agent-card bg-zinc-950 border border-cyan-500/20 rounded-2xl p-8">
          <h3 class="text-cyan-400 text-xl mb-4">⟐ Legal Research Agent</h3>
          <p class="text-gray-400 mb-6">Multi-agent legal reasoning system using IRAC framework with zero-trust citation verification.</p>
          <div class="text-xs uppercase tracking-widest text-purple-400">CrewAI • Redis Memory • CourtListener</div>
        </div>

        <div class="agent-card bg-zinc-950 border border-purple-500/20 rounded-2xl p-8">
          <h3 class="text-purple-400 text-xl mb-4">⟐ Financial Truth Agent</h3>
          <p class="text-gray-400 mb-6">Fine-tuned Phi-3 model trained to refuse unsupported claims and cite SEC filings accurately.</p>
          <div class="text-xs uppercase tracking-widest text-cyan-400">QLoRA • RAG • Refusal Training</div>
        </div>

        <div class="agent-card bg-zinc-950 border border-pink-500/20 rounded-2xl p-8">
          <h3 class="text-pink-400 text-xl mb-4">⟐ Business Intelligence Agent</h3>
          <p class="text-gray-400 mb-6">Natural language analytics agent with deterministic SQL generation and anomaly detection.</p>
          <div class="text-xs uppercase tracking-widest text-emerald-400">LiteLLM • PostgreSQL • Function Calling</div>
        </div>
      </div>
    </div>
  </section>

  <!-- Featured Systems -->
  <section id="systems" class="py-24 bg-black/60">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-16">Featured AI Systems</h2>
      <!-- Add your project cards here similar to above but more detailed -->
      <div class="text-center text-gray-400">
        [Add your 3-4 best projects here with links, tech stack, and impact metrics]
      </div>
    </div>
  </section>

  <!-- Research -->
  <section id="research" class="py-24">
    <div class="max-w-4xl mx-auto px-6 text-center">
      <h2 class="text-4xl font-bold mb-12">Research & Thought</h2>
      <div class="space-y-8 text-left">
        <a href="#" class="block p-6 bg-zinc-900/50 hover:bg-zinc-900 rounded-2xl border border-gray-700 hover:border-cyan-400 transition">
          <h3 class="text-lg font-semibold">Optimizing Predictive Models for Drug-Induced Suicidal Risk (IEEE, 2025)</h3>
        </a>
        <a href="#" class="block p-6 bg-zinc-900/50 hover:bg-zinc-900 rounded-2xl border border-gray-700 hover:border-cyan-400 transition">
          <h3 class="text-lg font-semibold">Optimizing Decision-Making Through Customer-Centric Market Basket Analysis</h3>
        </a>
      </div>
    </div>
  </section>

  <!-- Connect -->
  <section id="connect" class="py-24 border-t border-cyan-500/10">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-5xl font-bold mb-6">Let's Build the Future Together</h2>
      <p class="text-xl text-gray-400 mb-10">Open to full-time roles, consulting, and collaborations in Agentic AI.</p>
      
      <div class="flex flex-wrap justify-center gap-4">
        <a href="https://linkedin.com/in/syed-muhtasim-3308611a6" class="px-8 py-4 bg-zinc-900 hover:bg-zinc-800 rounded-full border border-cyan-400 flex items-center gap-2">
          <i class="fab fa-linkedin"></i> LinkedIn
        </a>
        <a href="https://huggingface.co/Abrar144" class="px-8 py-4 bg-zinc-900 hover:bg-zinc-800 rounded-full border border-yellow-400 flex items-center gap-2">
          <i class="fa-brands fa-hugging-face"></i> Hugging Face
        </a>
        <a href="mailto:abrarmuhtasim400@gmail.com" class="px-8 py-4 bg-gradient-to-r from-cyan-500 to-purple-600 rounded-full font-semibold">
          Get In Touch
        </a>
      </div>
    </div>
  </section>

  <footer class="text-center py-10 text-xs text-gray-500 font-mono">
    © 2025 • Built as an autonomous system by Abrar Muhtasim
  </footer>

</body>
</html>
