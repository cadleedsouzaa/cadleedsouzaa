<!-- Top Animated Banner -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,16,26,30&height=200&section=header&text=Cadlee%20D%20Souza&fontSize=48&fontAlignY=38&animation=fadeIn&fontColor=ffffff&desc=ML%20Engineer%20%C2%B7%20Audio%20AI%20%C2%B7%20Full-Stack&descAlignY=60&descSize=18" width="100%" alt="Cadlee D Souza" />

  <!-- Animated Typing Header with Space Grotesk -->
  <a href="https://deepecho.abrdns.com" target="_blank">
    <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=22&duration=2800&pause=1200&color=38BDF8&center=true&vCenter=true&width=620&lines=I+teach+machines+to+hear+the+difference+between+real+and+fake+%F0%9F%8E%99%EF%B8%8F;Building+DeepEcho+%E2%80%94+deepfake+speech+detection;PyTorch+%C2%B7+WavLM+%C2%B7+FastAPI+%C2%B7+Next.js" alt="Typing intro" />
  </a>
  <br><br>

  <!-- Badges -->
  <a href="https://deepecho.abrdns.com" target="_blank">
    <img src="https://img.shields.io/badge/DeepEcho-live_demo-00E676?style=for-the-badge&logo=googlechrome&logoColor=black" alt="DeepEcho live demo" />
  </a>
  <a href="https://www.linkedin.com/in/cadlee-dsouza/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=cadleedsouzaa&color=38bdf8&style=for-the-badge&label=VIEWS" alt="Profile views" />
</div>

---

### 👋 Hey, I'm Cadlee

I build ML systems that ship: from model experiments to a live API that real people can hit. My focus is **audio AI** and **deepfake speech detection**, with enough full-stack engineering to put a real-world product around the model.

- 🎙️ **Flagship Project**: Building **[DeepEcho](https://deepecho.abrdns.com/)** — an end-to-end deepfake speech detection platform with millisecond temporal resolution.
- 🔬 **Exploring**: Self-supervised speech representations (WavLM/HuBERT), learnable layer fusion, threshold calibration, and robustness to unseen neural vocoders.
- ⚡ **Competitive Coding & DSA**: Active practice in **C++** (graphs, dynamic programming, system algorithms).
- 💬 **Ask me about**: Acoustic ML, WavLM embeddings, PyTorch inference optimization, and async FastAPI services.

---

### 🎙️ Flagship: DeepEcho

> Detects AI-synthesized and voice-cloned speech with millisecond-level splice boundary detection, served behind a live web app.

```mermaid
flowchart LR
    A[🎤 Audio upload] --> B[Preprocess<br/>resample · normalize · chunk]
    B --> C[WavLM-Large<br/>25-layer embeddings]
    C --> D[Learned Layer Fusion<br/>& Classifier Head]
    D --> E{Score vs<br/>calibrated threshold}
    E -->|above| F[🚨 Synthetic]
    E -->|below| G[✅ Authentic]
```

| Specification | Details |
| :--- | :--- |
| **Model** | `WavLM-Large` backbone (317M params) + Learnable Softmax Layer Aggregation + Binary Classification Head |
| **Serving** | Async `FastAPI` (20.05ms temporal hop; frame-level boundary localization) |
| **Benchmark** | In-The-Wild dataset (31,779 clips) & MLAAD multi-generator testbed |
| **Results** | **8.02% EER** on In-The-Wild · **0.9825 F1-Score** on MLAAD held-out |
| **Links** | 🌐 **[Live Demo](https://deepecho.abrdns.com/)** · 💻 **[Source Code](https://github.com/cadleedsouzaa/DeepEcho---Deep-Fake-Audio-Detection)** |

---

### 🧰 Other Builds

| Project | What It Is | Stack |
| :--- | :--- | :--- |
| **[DealRoom](https://github.com/cadleedsouzaa/DealRoom)** | Real-time deal negotiation and collaboration workspace | Next.js · TypeScript |
| **[PolicyGate](https://github.com/cadleedsouzaa/PolicyGate)** | Automated policy compliance auditing and access verification engine | Python · Security |
| **[CultureVerse](https://github.com/cadleedsouzaa/cultureverse-final)** | Interactive cultural heritage discovery and exploration platform | React · TypeScript |
| **[MGD Noise Removal](https://github.com/cadleedsouzaa/Salt-Pepper-Noise-Removal-Using-MGD)** | Impulse noise reduction preserving sharp edge boundaries via Modified Gradient Descent | Python · OpenCV · NumPy |
| **[PlacementTraining](https://github.com/cadleedsouzaa/PlacementTraining)** | Data structures & algorithm implementations: graphs, DP, competitive programming | C++ |

---

### 🛠️ Stack

<div align="center">
  <p><strong>ML & Audio AI</strong></p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,opencv,sklearn&theme=dark" alt="ML Stack" />

  <p><strong>Backend & Web</strong></p>
  <img src="https://skillicons.dev/icons?i=fastapi,nodejs,react,nextjs,ts,tailwind&theme=dark" alt="Web Stack" />

  <p><strong>Systems & Tools</strong></p>
  <img src="https://skillicons.dev/icons?i=cpp,docker,linux,git,vercel&theme=dark" alt="Tools & Systems" />
</div>

---

### 📊 Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=cadleedsouzaa&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117" />
    <img src="https://github-readme-stats.vercel.app/api?username=cadleedsouzaa&show_icons=true&hide_border=true" width="410" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=cadleedsouzaa&theme=tokyonight&hide_border=true&background=0d1117" />
    <img src="https://streak-stats.demolab.com/?user=cadleedsouzaa&hide_border=true" width="410" alt="GitHub streak" />
  </picture>

  <!-- Optional: contribution snake. Set up Platane/snk Action, then uncomment:
  <img src="https://raw.githubusercontent.com/cadleedsouzaa/cadleedsouzaa/output/github-snake-dark.svg" alt="Contribution snake" />
  -->
</div>

<br>

<div align="center">
  <sub>Open to ML / audio-AI collaborations and engineering roles · reach me on <a href="https://www.linkedin.com/in/cadlee-dsouza/">LinkedIn</a></sub>
  <br><br>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,16,26,30&height=90&section=footer" width="100%" alt="Footer Banner" />
</div>

