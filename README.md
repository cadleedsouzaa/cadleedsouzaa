<!-- Top Animated Banner -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,16,26,30&height=200&section=header&text=Cadlee%20D%20Souza&fontSize=48&fontAlignY=38&animation=fadeIn&fontColor=ffffff&desc=ML%20Engineer%20%C2%B7%20Audio%20AI%20%C2%B7%20Full-Stack&descAlignY=60&descSize=18" width="100%" alt="Cadlee D Souza" />

  <!-- Animated Typing Header (Space Grotesk - Perfectly Centered, Zero Clipping) -->
  <a href="https://deepecho.abrdns.com" target="_blank">
    <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=20&duration=2800&pause=1200&color=38BDF8&center=true&vCenter=true&width=750&lines=I+teach+machines+to+hear+real+vs+fake+audio+%F0%9F%8E%99%EF%B8%8F;Building+DeepEcho+%E2%80%94+Deepfake+Audio+Detection+%F0%9F%94%A5;PyTorch+%E2%80%A2+WavLM-Large+%E2%80%A2+FastAPI+%E2%80%A2+Next.js+%E2%9A%A1;Detecting+Voice+Clones+%26+Spliced+Speech+at+Scale+%F0%9F%94%AC" alt="Typing intro" />
  </a>
  <br><br>

  <!-- Badges (Cleanly linked without underline artifacts) -->
  <a href="https://deepecho.abrdns.com" target="_blank"><img src="https://img.shields.io/badge/DeepEcho-live_demo-00E676?style=for-the-badge&logo=googlechrome&logoColor=black" alt="DeepEcho live demo" /></a>&nbsp;<a href="https://www.linkedin.com/in/cadlee-dsouza/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;<img src="https://komarev.com/ghpvc/?username=cadleedsouzaa&color=38bdf8&style=for-the-badge&label=VIEWS" alt="Profile views" />
</div>

---

### 👋 Hey, I'm Cadlee

I build ML systems that ship: from model research to high-throughput, low-latency live APIs. My specialization is **audio AI** and **deepfake speech forensics**, backed by strong full-stack engineering to build complete products around models.

- 🎙️ **Flagship**: Creator of **[DeepEcho](https://deepecho.abrdns.com/)** — live forensic platform detecting synthetic, cloned, and spliced speech at 20ms frame resolution.
- 🔬 **Research Focus**: Self-supervised speech representations (`WavLM-Large`), learnable layer-wise softmax aggregation, and vocoder artifact analysis.
- ⚡ **Algorithmic Practice**: Actively solving complex algorithmic problems in **C++** (graphs, dynamic programming, system optimization).
- 💬 **Ask me about**: Acoustic feature extraction, WavLM embeddings, PyTorch inference optimization, and async FastAPI microservices.

---

### 🎙️ Flagship Architecture: DeepEcho

> Real-time acoustic intelligence platform identifying synthesized, cloned, and spliced speech with millisecond-level splice boundary detection (20.05ms frame hop).

```mermaid
flowchart LR
    A[🎤 Audio Input] --> B[Preprocess<br/>16kHz · normalize · chunk]
    B --> C[WavLM-Large<br/>25-layer embeddings]
    C --> D[Learned Layer Fusion<br/>Softmax Attention]
    D --> E[Classification Head<br/>Linear · GELU · Dropout]
    E --> F{Calibrated<br/>Threshold}
    F -->|Score > Threshold| G[🚨 Synthetic Voice]
    F -->|Score ≤ Threshold| H[✅ Authentic Speech]
```

| Benchmark Metric | In-The-Wild (31,779 clips) | MLAAD Multi-Generator Testbed |
| :--- | :--- | :--- |
| **Performance** | **8.02% EER** (Equal Error Rate) | **0.9825 F1-Score** |
| **Resolution** | **20.05ms frame hop** (detects exact splice boundaries) | Evaluated across 39 generative voice engines |
| **Links** | 🌐 **[Live Web App](https://deepecho.abrdns.com/)** | 💻 **[GitHub Repository](https://github.com/cadleedsouzaa/DeepEcho---Deep-Fake-Audio-Detection)** |

---

### 🌟 Featured Projects Portfolio

<table align="center" width="100%">
  <thead>
    <tr>
      <th width="32%">Project</th>
      <th width="48%">Description</th>
      <th width="20%">Stack & Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <b>🎙️ <a href="https://deepecho.abrdns.com">DeepEcho</a></b>
        <br>
        <i>Deepfake Audio Detection</i>
        <br>
        <span style="color: #00E676; font-size: 11px; font-weight: bold;">● LIVE IN PRODUCTION</span>
      </td>
      <td>
        Forensic audio intelligence platform detecting synthetic speech and voice clones. Analyzes acoustic spectrograms and 25 WavLM transformer layers with 20ms boundary resolution.
      </td>
      <td>
        <a href="https://deepecho.abrdns.com">
          <img src="https://img.shields.io/badge/Live_Demo-deepecho.abrdns.com-00E676?style=flat-square&logo=googlechrome&logoColor=black" alt="Live Demo" />
        </a>
        <br>
        <a href="https://github.com/cadleedsouzaa/DeepEcho---Deep-Fake-Audio-Detection">
          <img src="https://img.shields.io/badge/Code-GitHub-1f6feb?style=flat-square&logo=github" alt="GitHub Repo" />
        </a>
        <br>
        <code>Python</code> <code>PyTorch</code> <code>WavLM</code>
      </td>
    </tr>
    <tr>
      <td>
        <b>🛡️ <a href="https://github.com/cadleedsouzaa/PolicyGate">PolicyGate</a></b>
        <br>
        <i>Automated Governance & Auditing</i>
      </td>
      <td>
        Policy enforcement and access compliance framework designed to audit configurations, detect compliance drift, and enforce organizational rules automatically.
      </td>
      <td>
        <a href="https://github.com/cadleedsouzaa/PolicyGate">
          <img src="https://img.shields.io/badge/Code-GitHub-1f6feb?style=flat-square&logo=github" alt="GitHub Repo" />
        </a>
        <br>
        <code>Python</code> <code>Automation</code> <code>Security</code>
      </td>
    </tr>
    <tr>
      <td>
        <b>💼 <a href="https://github.com/cadleedsouzaa/DealRoom">DealRoom</a></b>
        <br>
        <i>Deal Negotiation & Collaboration Hub</i>
      </td>
      <td>
        Full-stack digital workspace providing structured negotiation pipelines, document handling, and real-time collaboration workflows.
      </td>
      <td>
        <a href="https://github.com/cadleedsouzaa/DealRoom">
          <img src="https://img.shields.io/badge/Code-GitHub-1f6feb?style=flat-square&logo=github" alt="GitHub Repo" />
        </a>
        <br>
        <code>Next.js</code> <code>TypeScript</code> <code>Tailwind</code>
      </td>
    </tr>
    <tr>
      <td>
        <b>🖼️ <a href="https://github.com/cadleedsouzaa/Salt-Pepper-Noise-Removal-Using-MGD">Noise Removal (MGD)</a></b>
        <br>
        <i>Digital Image Processing</i>
      </td>
      <td>
        Impulse noise reduction algorithm utilizing Modified Gradient Descent (MGD) optimization for high-fidelity image restoration while preserving sharp edge boundaries.
      </td>
      <td>
        <a href="https://github.com/cadleedsouzaa/Salt-Pepper-Noise-Removal-Using-MGD">
          <img src="https://img.shields.io/badge/Code-GitHub-1f6feb?style=flat-square&logo=github" alt="GitHub Repo" />
        </a>
        <br>
        <code>Python</code> <code>OpenCV</code> <code>NumPy</code>
      </td>
    </tr>
    <tr>
      <td>
        <b>🏛️ <a href="https://github.com/cadleedsouzaa/cultureverse-final">CultureVerse</a></b>
        <br>
        <i>Interactive Cultural Discovery</i>
      </td>
      <td>
        Interactive web application designed to explore global traditions, historical artifacts, and cultural heritage through an intuitive, modern responsive interface.
      </td>
      <td>
        <a href="https://github.com/cadleedsouzaa/cultureverse-final">
          <img src="https://img.shields.io/badge/Code-GitHub-1f6feb?style=flat-square&logo=github" alt="GitHub Repo" />
        </a>
        <br>
        <code>TypeScript</code> <code>React</code>
      </td>
    </tr>
    <tr>
      <td>
        <b>⚡ <a href="https://github.com/cadleedsouzaa/PlacementTraining">Algorithmic Engineering</a></b>
        <br>
        <i>DSA & System Optimization</i>
      </td>
      <td>
        Optimized implementations of core data structures, dynamic programming paradigms, graph traversal algorithms, and competitive programming patterns in C++.
      </td>
      <td>
        <a href="https://github.com/cadleedsouzaa/PlacementTraining">
          <img src="https://img.shields.io/badge/Code-GitHub-1f6feb?style=flat-square&logo=github" alt="GitHub Repo" />
        </a>
        <br>
        <code>C++</code> <code>DSA</code> <code>Algorithms</code>
      </td>
    </tr>
  </tbody>
</table>

---

### 🛠️ Tech Stack & Arsenal

<div align="center">
  <p><strong>ML & Audio AI</strong></p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,opencv,sklearn&theme=dark" alt="ML Stack" />

  <p><strong>Backend & Full-Stack</strong></p>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,react,nextjs,ts,tailwind&theme=dark" alt="Web Stack" />

  <p><strong>Systems & Tools</strong></p>
  <img src="https://skillicons.dev/icons?i=cpp,docker,linux,git,vercel&theme=dark" alt="Tools & Systems" />
</div>

---

### 📊 GitHub Activity & Analytics

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=cadleedsouzaa&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" />
    <img src="https://github-readme-stats.vercel.app/api?username=cadleedsouzaa&show_icons=true&hide_border=true" width="410" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=cadleedsouzaa&theme=tokyonight&hide_border=true&background=0d1117" />
    <img src="https://streak-stats.demolab.com/?user=cadleedsouzaa&hide_border=true" width="410" alt="GitHub streak" />
  </picture>
</div>

<br>

<div align="center">
  <sub>Open to ML / audio-AI collaborations and engineering roles · reach me on <a href="https://www.linkedin.com/in/cadlee-dsouza/">LinkedIn</a></sub>
  <br><br>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,16,26,30&height=90&section=footer" width="100%" alt="Footer Banner" />
</div>

