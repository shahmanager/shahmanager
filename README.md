<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=10,25,47,0,180,216,114,9,183&height=220&section=header&text=Arya%20Shah&fontSize=48&fontAlignY=36&desc=Builder%20%E2%80%A2%20AI%20Agents%20%E2%80%A2%20Full%20Stack%20%E2%80%A2%20Systems%20Tinkerer&descAlignY=62&descAlign=50&fontColor=ffffff" width="100%" />

  <a href="https://github.com/shahmanager">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00B4D8&center=true&vCenter=true&width=650&lines=Developer+%26+Computer+Science+Builder;Exploring+Autonomous+AI+Agents+%26+Voice+Pipelines;Tinkering+with+Full+Stack+%26+Embedded+Systems;Building+Things+From+First+Principles" alt="Typing SVG" />
  </a>

  <p align="center">
    <a href="mailto:aryashah232004@gmail.com">
      <img src="https://img.shields.io/badge/Email-aryashah232004%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://github.com/shahmanager">
      <img src="https://img.shields.io/badge/GitHub-shahmanager-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
    </a>
  </p>
</div>

---

### 👨‍💻 About Me

Hi! I am a developer and builder passionate about AI systems, agentic workflows, and hands-on systems programming. I enjoy building functional projects from first principles, learning how complex systems work under the hood, and connecting high level AI models with practical applications and physical hardware.

▸ 🔭 **What I am working on:** Voice conversational agents, multi agent coordination setups, and full stack tools.  
▸ ⚡ **Areas of exploration:** Real time speech pipelines (Pipecat, Gemini Live S2S), edge computing with Cloudflare Workers, and embedded C++ firmware.  
▸ 🔬 **Curiosities:** How autonomous agents manage long term memory, privacy preserving distributed ML (Federated Learning), and writing clean, reliable code.  
▸ 💬 **Let's talk about:** Python, TypeScript, React, AI experiments, hardware tinkering, and building things that solve real problems.

---

### 🛠️ Tech Stack & Tooling

<div align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,js,cpp,c,postgres,sqlite,redis,docker,git,linux,react,fastapi,cloudflare&perline=14" alt="Skill Icons" />
</div>

<br />

<table>
  <tr>
    <td width="22%"><b>Languages</b></td>
    <td>Python, TypeScript, JavaScript, C++, C, SQL, Bash</td>
  </tr>
  <tr>
    <td width="22%"><b>AI &amp; Frameworks</b></td>
    <td>PyTorch, Gemini API, LiteLLM, Pipecat Voice AI, Hugging Face</td>
  </tr>
  <tr>
    <td width="22%"><b>Web &amp; Backend</b></td>
    <td>React, Node.js, FastAPI, Cloudflare Workers, Cloudflare D1, Tailwind CSS</td>
  </tr>
  <tr>
    <td width="22%"><b>Tools &amp; Storage</b></td>
    <td>PostgreSQL, SQLite (FTS5), Redis, Docker, Git, GitHub Actions, Linux</td>
  </tr>
  <tr>
    <td width="22%"><b>Hardware &amp; Systems</b></td>
    <td>Embedded C++, Firmware Experiments, Hardware Interfacing</td>
  </tr>
</table>

---

### 🔀 Architecture Pipeline: Real Time Voice Agent

```mermaid
flowchart LR
    A["Caller Audio Stream"] --> B["Pipecat Audio Pipeline"]
    B --> C["Gemini Live S2S Engine"]
    C --> D{"Grounding & Safety"}
    D -->|"Query Cited Passages"| E[("SQLite FTS5 Manuals")]
    D -->|"Safety Short Circuit"| F["Safety Circuit Breaker"]
    D -->|"Synthesize Response"| G["Sarvam AI Speech"]
    G --> H["Live Telephony Stream"]

    style A fill:#0d1117,stroke:#58a6ff,stroke-width:2px,color:#c9d1d9
    style B fill:#0d1117,stroke:#58a6ff,stroke-width:2px,color:#c9d1d9
    style C fill:#0d1117,stroke:#bc8cff,stroke-width:2px,color:#c9d1d9
    style D fill:#0d1117,stroke:#f0883e,stroke-width:2px,color:#c9d1d9
    style E fill:#0d1117,stroke:#3fb950,stroke-width:2px,color:#c9d1d9
    style F fill:#0d1117,stroke:#f85149,stroke-width:2px,color:#c9d1d9
    style G fill:#0d1117,stroke:#58a6ff,stroke-width:2px,color:#c9d1d9
    style H fill:#0d1117,stroke:#58a6ff,stroke-width:2px,color:#c9d1d9
```

---

### 🚀 Projects &amp; Experiments

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/shahmanager/voice-on-call-ai-agent">🎙️ Voice On-Call AI Agent (Shubh)</a></h3>
      <p align="center">A voice agent exploring live speech to speech conversations with grounded knowledge retrieval.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Pipecat_Voice_AI-6C5CE7?style=flat-square&logo=webrtc&logoColor=white" />
        <img src="https://img.shields.io/badge/Gemini_Live_S2S-4285F4?style=flat-square&logo=google&logoColor=white" />
        <img src="https://img.shields.io/badge/Sarvam_AI-FF6F00?style=flat-square" />
        <img src="https://img.shields.io/badge/Python_3-3776AB?style=flat-square&logo=python&logoColor=white" />
      </p>
      <ul>
        <li><b>Speech to Speech:</b> Conversational audio in Indian English and Hinglish using Gemini Live S2S and Pipecat.</li>
        <li><b>Grounded Answers:</b> Uses SQLite FTS5 text search over product manuals to cite passages instead of guessing.</li>
        <li><b>Safety Guardrails:</b> Simple keyword interceptors that prioritize user safety before triggering model calls.</li>
        <li><b>Telephony:</b> Streams live audio over WebSockets with state checkpointing between turns.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/shahmanager/jarvis-meets-friday">🤖 Jarvis Meets Friday</a></h3>
      <p align="center">An experimental two agent setup exploring cloud execution, laptop verification, and memory.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Multi_Agent-6C5CE7?style=flat-square" />
        <img src="https://img.shields.io/badge/Cloud_Execution-2496ED?style=flat-square" />
      </p>
      <ul>
        <li>Separates background cloud task execution from local laptop evidence review.</li>
        <li>Explores durable agent memory and structured messaging between collaborating agents.</li>
        <li>Focuses on clear progress logging and verifiable completion criteria.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/shahmanager/frontier">⚡ Frontier</a></h3>
      <p align="center">A lightweight Python utility exploring multi agent file leases and SHA based build verification.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Python_3-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Stdlib_Only-000000?style=flat-square" />
        <img src="https://img.shields.io/badge/SHA_Proof-00C896?style=flat-square" />
      </p>
      <ul>
        <li>Built in a single standard library Python file with zero third party dependencies.</li>
        <li>Uses simple file leases to prevent race conditions during concurrent agent edits.</li>
        <li>Computes SHA hashes to ensure clean context boundaries and reproducible build steps.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/shahmanager/federated-credit-risk">🔒 Federated Credit Risk</a></h3>
      <p align="center">A practical simulation of privacy preserving machine learning across banking nodes using FedAvg.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Federated_Learning-FF6F00?style=flat-square" />
        <img src="https://img.shields.io/badge/FedAvg-107C41?style=flat-square" />
      </p>
      <ul>
        <li>Simulates distributed financial institutions training local models on private client data.</li>
        <li>Aggregates model weights centrally via Federated Averaging without sharing raw records.</li>
        <li>Explores the balance between predictive performance and data privacy.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 📊 GitHub Activity &amp; Telemetry

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=shahmanager&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="Contribution Telemetry Graph" />
  
  <br /><br />
  
  <table border="0">
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=shahmanager&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" alt="Arya's GitHub Stats" />
      </td>
      <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shahmanager&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Top Languages" />
      </td>
    </tr>
  </table>
  
  <br />
  
  <img src="https://streak-stats.demolab.com/?user=shahmanager&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakNum=58A6FF&sideNums=58A6FF&dates=8B949E" alt="GitHub Streak" />
</div>

<br />

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=10,25,47,0,180,216,114,9,183&height=100&section=footer" width="100%" />
</div>
