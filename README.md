# Hi, I'm Utkarsh 👋

> *Systems programmer, game dev, and builder of things that probably shouldn't exist.*

ML/AI research engineer. I build generative AI that listens, talks back and draws, and I get it running in
real time: on GPU clusters for live shows, and on an 8 GB robot.

🌿 **Portfolio:** [utkarshyadav009.github.io/portfolio](https://utkarshyadav009.github.io/portfolio/)

---

## 🎭 CoSTAR lab, Abertay University (2026)

Two months as an AI/ML Researcher on CoSTAR, the UK national lab for virtual production and live performance.

| Project | What it is | Headline |
|---|---|---|
| [**CharacterPlex**](https://github.com/utkarshyadav009/CharacterPlex) | NVIDIA PersonaPlex 7B fine-tuned to play a character, follow story beats and take live director notes, with laughs and sighs on cue | +66 pts director-note obedience; full-parameter run on 8× H200 |
| [**PersonaPlex at scale**](https://github.com/utkarshyadav009/personaplex-scale) | Full-duplex speech-to-speech served with vLLM-Omni: batched steps, paged KV cache per caller | 12 real-time calls per 48 GB GPU |
| [**Speech Systems**](https://github.com/utkarshyadav009/speech-systems) | Say it on stage and watch it appear: speech → image → 3D → rigged, animated character, for improv | 0.86 s from speech to picture |
| **Soran Labs** | A world model that generates relightable 3D Gaussian splat scenes, ported to smaller GPUs with lazy loading, offloading and quantisation | Running on the new server in a week |

---

## 🤖 BMO: an embodied AI companion (MSc thesis, Distinction)

A small robot in a 3D-printed case that sees, hears and talks with no cloud, on a Jetson Orin Nano Super.

- **Perception:** frozen V-JEPA 2 (video) and WavJEPA (audio) joined by a trained fusion bridge. 53% R@1
  audio-visual retrieval on a 1,545-clip VGGSound gallery.
- **Conversation:** an LFM2.5-350M speaker that answers first and a Qwen3-0.6B thinker for reasoning and tools,
  with turn-taking handled by a separate 1.3M-parameter head.
- **On the device:** [bmo_jetson](https://github.com/utkarshyadav009/bmo_jetson), a C++/CUDA engine running
  full-duplex Moshi at 64.5 ms per 80 ms audio frame (4-bit weights, CUDA graphs, fused RVQ kernels, TensorRT codec).
- **Paper:** *Hearing What You See: Efficient Audio-Visual Retrieval from Frozen Encoders*, under review at ECIR
  2027 ([code](https://github.com/utkarshyadav009/AV-Fusion)).

Repos: [BMO-Project](https://github.com/utkarshyadav009/BMO-Project) · [bmo_jetson](https://github.com/utkarshyadav009/bmo_jetson) · [AV-Fusion](https://github.com/utkarshyadav009/AV-Fusion) · [diarization-pipeline](https://github.com/utkarshyadav009/diarization-pipeline)

---

## 🎮 Earlier

- [**Phase-Functioned Neural Network in UE5**](https://github.com/utkarshyadav009/Phase-Functioned-Neural-Network-UE5):
  a recreation of PFNN character locomotion inside Unreal Engine, with a custom plugin.
- Two years as an Associate Lecturer at London Metropolitan University, teaching games programming (C++),
  game design (Unity) and 3D (Blender).
- More games and graphics work on the [portfolio shelf](https://utkarshyadav009.github.io/portfolio/#shelf).

---

## 🛠️ Tech

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine-313131?style=flat-square&logo=unrealengine&logoColor=white)
![GLSL](https://img.shields.io/badge/GLSL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

---

## 📊 Stats

![Utkarsh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=utkarshyadav009&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=utkarshyadav009&layout=compact&theme=tokyonight&hide_border=true)

---

*Currently: looking for research engineering work in generative AI for creative technology.*
