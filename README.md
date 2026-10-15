# EkoLiving

**Your city. Your rules.** An original browser-based 3D life-simulation prototype set in a Lagos-inspired open city.

## Current prototype
- Three.js 3D scene with a street grid, sidewalks, trees, procedural buildings and named locations.
- Controllable character with walking/running, third-person and first-person camera modes.
- Moving traffic and ambient pedestrian NPCs.
- Enterable buildings with generated 3D interiors for apartments, homes, clubs, restaurants and offices.
- Interactions, work shifts, money, needs, food, rest, hygiene, social actions, map, garage and waypoint panels.
- Responsive HUD and minimap.

## Run locally
Serve the files over HTTP rather than opening `index.html` directly:

    python3 -m http.server 4173

Then open http://localhost:4173.

## Controls
- WASD / arrow keys: move or drive
- Shift: run
- E: interact / enter buildings and vehicles
- V: toggle first-person / third-person
- M: city map
- J: jobs
- Mouse: look around (click the world to lock pointer)
- Esc: close menus / leave interior

## Render deployment
Create a Render Static Site from this repository, leave the build command empty, and set publish directory to `.`.

## Roadmap
This is a playable foundation, not a finished GTA-scale game. Production work remains for collision/navigation, proper vehicle physics, authored interiors, save/load and backend accounts, mission scripting, audio, optimised asset streaming and multiplayer infrastructure.
