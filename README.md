# Space Freedom

A retro-style, 2D top-down space shooter game built entirely with modern Web technologies. **Space Freedom** delivers arcade-style action, dynamic enemy waves, intense boss fights, and deep hangar customization all running natively in your browser with zero external engine dependencies.

## Key Features

* **Pure HTML5 Canvas Engine**: Custom 2D rendering pipeline written in lightweight, native JavaScript.
* **Real-time Web Audio API**: Procedurally synthesized sound effects and audio generated entirely on-the-fly without heavy audio files.
* **Interactive Hangar Customization**: Upgrade weapon systems, hull durability, engine velocity, and shield capacity between missions.
* **Multi-Stage Campaign**: Escalating stage progression featuring distinct enemy movement patterns and challenging boss encounters.
* **Dynamic Weapon Power-Ups**: Collect mid-battle drops including spread shots, lasers, emergency repairs, and temporary shield boosts.

## Controls
- Movement: WASD or Arrow Keys
- Fire Weapon: Spacebar or Left Mouse Button
- Special / Ability: Shift or Right Mouse Button
- Pause / Menu: Esc or P

## Tech Stack

* **Frontend**: HTML5 Canvas, Vanilla JavaScript (ES6+)
* **Audio**: Web Audio API (Synthesizers & Oscillators)
* **Styling**: CSS3

## Project Folder
```text
space-freedom/
├── index.html          # Main HTML layout, canvas setup, and inline UI
├── assets/             # Sprite sheets, graphics, and static artwork
│   ├── images/
│   └── icons/
├── css/
│   └── style.css       # Game styling, hangar UI, and overlay menus
└── js/
    ├── audio.js        # Web Audio API synthesizer logic
    ├── engine.js       # Game loop, state manager, and collision detection
    ├── entities.js     # Player, enemies, bosses, and projectiles
    └── ui.js           # Hangar upgrades and HUD interaction
```
## Quick Start

No build tools, complex package managers, or server installations required.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/space-freedom.git](https://github.com/your-username/space-freedom.git)
   cd space-freedom
