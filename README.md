# 🎸🥁 Kinetic Strings & Drums

An interactive, minimal physics-and-motion musical playground built with **HTML5 Canvas** and the **Web Audio API**. Play guitar strings, tap geometric drum pads, or fling bouncing orbs across the stage to generate melodies and rhythms that transcribe in real time onto a scrolling musical staff.

🔗 **[Play the Live Demo Here](https://YOUR-USERNAME.github.io/kinetic-strings-and-drums/)** *(Replace `YOUR-USERNAME` with your GitHub username)*

---

## ✨ Features

- **6 Tuned Guitar Strings:** Standard tuning ($E_2, A_2, D_3, G_3, B_3, E_4$) with damped harmonic string vibration physics and dual-oscillator plucked synthesis.
- **4 Geometric Drum Pads:** Synthesized **Kick** (Circle), **Snare** (Hexagon), **Hi-Hat** (Diamond), and **Tom** (Triangle) built purely with Web Audio oscillators and noise buffers.
- **Autonomous Motion Orbs:** Physics-driven orbs bounce around the canvas, plucking strings as they cross them and rebounding off drum shapes.
- **Real-Time Sheet Music Staff:** Every note and percussion hit is plotted live at the bottom of the screen using standard oval note heads for guitar pitches and `X` note heads for percussion.
- **Zero Dependencies:** Contained entirely in a single `index.html` file with no external libraries, frameworks, or audio samples required.

---

## 🎮 Controls & Interaction

| Action | Result |
| :--- | :--- |
| **Drag across strings** | Strums the guitar strings manually |
| **Click a geometric shape** | Triggers the drum pad |
| **Click empty space** | Spawns a new bouncing orb |
| **Click & drag an orb** | Grabs and flings the orb at custom speed and angle |
| **Top HUD Buttons** | Spawn orbs, clear orbs, clear the sheet music, or toggle audio mute |

---

## 🚀 Running Locally

Because the app has zero external dependencies, you don't need `npm` or a build step:

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/kinetic-strings-and-drums.git](https://github.com/YOUR-USERNAME/kinetic-strings-and-drums.git)
   ```
2. Open `index.html` directly in any modern web browser (Chrome, Firefox, Safari, Edge).

---

## 🛠️ Tech Stack

- **HTML5 Canvas 2D API** — 60 FPS rendering for string wave curves, polygon geometry, particle ripples, and scrolling musical notation.
- **Web Audio API** — Real-time procedural sound synthesis (`OscillatorNode`, `BiquadFilterNode`, `GainNode`, and white-noise `AudioBuffer` generation).
- **Vanilla JavaScript (ES6+)** — Custom 2D collision detection and line-crossing physics.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.