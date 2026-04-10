# 🚀 Space Debris Cleaner
**CMPT 461 Immersive Computing — Trinity Western University — 2026**

> Created by: **[YOUR NAME]** | Student ID: **[YOUR ID]**

---

## Play the Game
▶ **[Launch Game](https://[YOUR-USERNAME].github.io/[REPO-NAME]/)**

📖 **[Read the Manual](https://[YOUR-USERNAME].github.io/[REPO-NAME]/manual.html)**

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

## Controls
| Action | How |
|--------|-----|
| Look around | Move head (mobile gyroscope) / click-drag (desktop) |
| Target debris | Centre reticle on object |
| Zap debris | Hold gaze for 1.5 s (normal) · 1.2 s (hard) |
| Enter VR | Tap 👓 icon (bottom-right) |

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
