# Hi, I'm Utkarsh 👋

> *Systems programmer, game dev, and builder of things that probably shouldn't exist.*

I like working close to the metal — shaders, physics, neural networks, embedded AI. If it involves C++, Unreal Engine, or a Jetson running on a prayer, I'm interested.

---

## 🔨 What I'm Building

### 🤖 [BMO — Embodied AI Companion](https://github.com/utkarshyadav009/BMO-Project)

> *"BMO, we need you to be our friend forever."*

A fully local AI companion running on an **NVIDIA Jetson Orin Nano 8GB**, inspired by the Adventure Time character. Not a chatbot in a box — BMO has **synthetic aliveness**: internal drives, temporal awareness, and a persistent identity that deepens over time.

**Key systems:**

| System | Tech | What it does |
|--------|------|-------------|
| 🎭 **Face Engine** | C++17 · Raylib · GLSL | Procedural SDF-based face — 13 eye types, Catmull-Rom mouth splines, spring-damper expression physics |
| 🧠 **Cognitive Core** | Active Inference · pymdp · Gemma 2 2B (INT4) | Dual System 1/2 architecture; personality encoded as a POMDP preference matrix, not a system prompt |
| 🎤 **Voice Engine** | Python · WhisperX · Moshi · LoRA | Full dataset pipeline from raw episodes → speaker separation → tone-labelled clips → SFT fine-tuned voice |
| 💾 **Memory** | LanceDB · Agglomerative Clustering | Tiered MaRS architecture with sleep-cycle consolidation — long-term memory grows in meaning, not volume |

```
BMO's personality is not a prompt.
It's a C-Matrix of prior preferences in a generative model.
C_affect[2] = +4.0   # Strong preference for observing user happiness
C_affect[0] = -5.0   # Strong aversion to observing user anger
```

---

### 🎮 [Phase-Functioned Neural Network — UE5](https://github.com/utkarshyadav009/Phase-Functioned-Neural-Network-UE5) ⭐ 15

A from-scratch recreation of the **Phase-Functioned Neural Network** locomotion system inside Unreal Engine 5. PFNN is the technique behind some of the most fluid character movement in modern games — it uses a neural network whose weights are blended based on a phase variable extracted from the animation cycle.

**Stack:** C++ · Unreal Engine 5 · Neural Networks · Character Animation

---

## 🛠️ Tech

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-313131?style=flat-square&logo=unrealengine&logoColor=white)
![GLSL](https://img.shields.io/badge/GLSL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

---

## 📊 Stats

![Utkarsh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=utkarshyadav009&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=utkarshyadav009&layout=compact&theme=tokyonight&hide_border=true)

---

## 🌐 Find Me

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://utkarshyadav009.github.io/portfolio/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/utkarshyadav009)

---

*Currently: making BMO real. Slowly.*
