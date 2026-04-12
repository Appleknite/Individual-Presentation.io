# 🚀 Space Debris Cleaner
**CMPT 461 Immersive Computing — Trinity Western University — 2026**

> Created by: **Dev Gandhi** | Student ID: **649105**

---

## Play the Game
▶ **[Launch Game](https://Appleknite.github.io/Individual-Presentation.io/main.html)**

📖 **[Read the Manual](https://Appleknite.github.io/Individual-Presentation.io/manual.html)**

---

## About
Space Debris Cleaner is a mobile VR game built with [A-Frame](https://aframe.io).
You control an orbital station's defence AI — using only your **gaze** (no hands),
lock on to space junk and zap it before it reaches you.
Avoid operational satellites or pay the penalty!

## Features
- 🎯 Gaze-based dwell-to-zap control (no hands)
- 📱 Stereoscopic VR — Google Cardboard compatible
- 🌌 2 levels of increasing difficulty
- 🎵 Synthesized ambient music (Web Audio API, mutable)
- 💥 Sound effects: zap, explosion, life-lost, level-up
- ⭐ Always-visible scoreboard (2D HUD + in-scene VR panel)
- 🛰 3 object types with custom canvas-generated textures
- ☄️ Collision detection — debris reaching you costs a life
- ⚙ Setup menu: music on/off, Normal/Hard difficulty

## How to Run Locally
```bash
# Python 3
python -m http.server 8080
# Then open http://localhost:8080 in Chrome
```
> Do **not** open `index.html` via `file://` — use a local server.

## File Structure
```
index.html    — game (single self-contained file)
manual.html   — player manual
README.md     — this file
```

## Built With
- [A-Frame 1.4.2](https://aframe.io) — WebXR framework
- Web Audio API — all audio synthesized in-browser
- Canvas API — all textures generated procedurally

---
*No external assets required beyond the A-Frame CDN script.*
