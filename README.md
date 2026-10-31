# 👻 Anti-Gravity AI: Ghost in the Machine
### 🏆 Official Entry for the Hacktoberfest Open-Source AI Challenge

demo : - https://babatheslayer.github.io/HACKTOBER-FEST/

> **"In the void between clock cycles, mass is an illusion, friction is zero, and momentum is immortal."**

![Hacktoberfest](https://img.shields.io/badge/Hacktoberfest-2026-orange?style=for-the-badge&logo=hacktoberfest)
![AI Model](https://img.shields.io/badge/Transformers.js-Client--Side%20ONNX-00f3ff?style=for-the-badge&logo=huggingface)
![Physics](https://img.shields.io/badge/Zero--G%20Physics-Frictionless%202D-9d4edd?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🌌 Overview

**Anti-Gravity AI: Ghost in the Machine** is a 2D zero-gravity physics simulator and ambient AI playground assembled entirely inside a single, zero-dependency `index.html` file.

Set in an abandoned deep-space mainframe where gravity has been switched off ($G = 0.0$), users interact with an autonomous, spectral AI astronaut—**"The Zero-G Ghost"**—who drifts eternally through the vacuum, commenting on decaying bytecodes and answering cosmic inquiries.

### 🕹️ Live Demo / Quick Run
No build steps, Node.js installations, or API keys needed!
1. Double-click `index.html` in any modern web browser (Chrome, Edge, Firefox, Brave, Safari).
2. Or serve locally with any static server:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   ```

---

## ✨ Key Features

### 🚀 1. Frictionless Zero-G Physics Engine (HTML5 Canvas)
- **Conservation of Momentum:** Without friction or atmosphere, spawned objects maintain linear and angular momentum indefinitely.
- **2D Elastic Vector Collisions:** Rigorous momentum & impulse exchange upon collision between matter.
- **Interactive Spawn Palette:**
  - 🚀 **Space Debris:** Asteroid fragments, busted satellite solar panels, and scrap iron.
  - 💾 **Abandoned Code Packets:** Glitching ROM cartridges and RAM blocks stamped with real runtime errors (`0xDEADBEEF`, `Segmentation fault (core dumped)`, `undefined is not a function`).
  - 🔮 **Haunted Nodes:** Pulsating ethereal energy cores that cast glowing quantum filament tethers to nearby nodes and exhibit harmonic resonance.
  - 🕳️ **Quantum Singularities:** Micro black holes exerting inverse-square gravitational pull on all surrounding matter.

### 👻 2. The Spectral Astronaut / "Ghost in the Machine"
- Procedural canvas creature with animated sine-wave bobbing, interactive cursor eye-tracking, glowing cybernetic visor, and ectoplasmic particle exhaust.
- Dynamic floating speech bubbles that react to user events and environment changes.
- **"Disturb the Ghost" Button / Shockwave Blast:** Rattles the ghost's containment field, triggering a high-velocity radial blast that scatters all matter across the screen with camera shake and audio glitching!

### 🧠 3. In-Browser Client-Side AI (Transformers.js / Hugging Face)
- Powered by `@xenova/transformers` running ONNX weights directly in WebAssembly/WebGL memory.
- **Zero API keys, zero rate limits, and 100% privacy-preserving:** Runs locally on the client's machine.
- **Dual Neural Pipeline:** Features an instant Spectral Quantum Heuristic generator while the Transformers.js neural weights load, ensuring zero freeze or loading delay.
- **Autonomous Observations:** The ghost periodically inspects the floating debris and code packets, speaking poetic commentary.

### 🎵 4. Procedural Web Audio Synthesizer
- **Zero external audio files:** Synthesizes low-frequency 55Hz space drone, metallic bounce impacts, ethereal harmonic chords, cyber chirps, and sub-bass shockwaves directly through the browser `AudioContext`.

---

## 🎛️ Controls & UI Guide

| Control | Description |
| :--- | :--- |
| **Click & Drag** | Set ejection vector and velocity to launch objects into 0-G space. |
| **Click Ghost** | Resonate directly with the ghost entity to disturb its float state. |
| **Double Click** | Trigger a localized vacuum impulse shockwave. |
| **TOGGLE GRAVITY** | Switch between pure $0.0G$ frictionless float, downward gravity pull, and reverse glitch float. |
| **DISTURB GHOST** | Triggers an emergency ectoplasmic detonation flinging all matter outward. |
| **Matter Palette** | Select between Space Debris, Code Packets, Haunted Nodes, and Singularities. |
| **CRT Toggle** | Switch retro phosphor scanlines and vignette on or off. |
| **DEV Submission Info** | Opens submission overview with one-click copyable DEV.to challenge report. |

---

## 🛠️ Tech Stack

- **Physics & Graphics:** Pure Vanilla HTML5 Canvas 2D API
- **Styling:** Tailwind CSS (via CDN) + Cyberpunk Scanline CSS
- **Machine Learning:** Hugging Face [Transformers.js](https://huggingface.co/docs/transformers.js)
- **Audio:** Native Web Audio API (`OscillatorNode`, `BiquadFilterNode`, `GainNode`)
- **Typography:** Orbitron & Share Tech Mono (Google Fonts)

---

## 📝 DEV.to Hacktoberfest Submission Template
To submit to the **Hacktoberfest Open-Source AI Challenge** on DEV:
1. Open the app and click **🏆 SUBMISSION INFO** in the top navigation bar.
2. Click **📋 Copy DEV Post Template**.
3. Paste directly into your draft at [dev.to/new](https://dev.to/new) under the `#hacktoberfest` tag!

---

*Crafted with 💜 for the Hacktoberfest Open-Source Community.*

