# GRID DASH

**GRID DASH** is a high-performance, web-based rhythm platformer inspired by *Geometry Dash*. It features a custom-built physics engine, procedural music generation, and a fully reactive environment, all contained within a single HTML file.

## 🎮 How to Play

1.  **Download** the `GridDash.html` file.
2.  **Open** the file in any modern web browser (Chrome, Firefox, Edge, Safari).
3.  **Click** anywhere to initialize the audio engine and start the game.

## 🕹️ Controls

| Action | Key / Input |
| :--- | :--- |
| **Jump** | `Spacebar`, `Up Arrow`, `Left Mouse Click`, or `Touch` |
| **Pause** | `Esc` or the `||` button on screen |
| **Restart Level** | `R` |
| **Main Menu** | `Tab` |
| **Customize** | `C` (Only in Menu/Pause screens) |

## 🌟 Features

### 3 Unique Levels
* **Stereo Bound (Easy):** A forgiving introduction featuring standard jumps and yellow jump pads. *Theme: Cyan/Tech.*
* **Lunar Orbit (Medium):** Increases the challenge with timing-based orbs, pink pads, and tighter platforming. *Theme: Purple/Neon.*
* **Crimson Fury (Hard):** A high-speed test of reflex featuring triple spikes, tight 1-block tunnel gaps, and "floor is lava" mechanics. *Theme: Red/Magma.*

### Engine & Visuals
* **Zero Dependencies:** The entire game runs from one file. No images, mp3s, or external libraries are loaded.
* **Procedural Music:** Uses the Web Audio API to synthesize unique chiptune/synthwave soundtracks in real-time for each level.
* **Reactive Backgrounds:** The game world pulses and flashes in sync with jumps, orbs, and pads.
* **120FPS Interpolation:** Physics run at a strict deterministic 120Hz, while visuals are interpolated to match your high-refresh-rate monitor for buttery smooth movement.
* **Particle Systems:** Custom particle effects for death, orbs, pads, and a vacuum effect at the finish line.

### Customization (Garage)
Press **'C'** in the menu to access the **Garage**.
* **Icons:** Choose from 6 procedurally drawn avatars (Cube, Grid, Cross, Creeper, Pilot, Companion).
* **Colors:** Select Primary and Secondary colors to paint your avatar and trail.

## 🛠️ Technical Details

* **Physics:** Axis-Aligned Bounding Box (AABB) collision with sub-pixel resolution and corner correction logic to prevent unfair deaths.
* **Rendering:** HTML5 Canvas API.
* **Audio:** Web Audio API (Oscillators and Gain Nodes) for music and SFX.
* **Architecture:** Fixed-timestep game loop with state interpolation.

## 📝 Credits

* **Concept & Code:** REDNAT
* **Inspiration:** RobTop Games (Geometry Dash)
