# Initial Prompt

Create a browser-based arcade game inspired by the classic 1981 vector-tunnel shooter *Tempest*, using Three.js.

## Goal

Build a fully playable single-page HTML/JavaScript game with a fast neon vector-tunnel shooter feel.

## Core Features

- Neon vector-graphics aesthetic on a black background
- 3D tunnel made from connected geometric lanes, like a wireframe tube viewed from one end
- Player ship constrained to move around the rim of the tunnel
- Enemies that crawl up the tunnel lanes toward the player
- Player bullets that travel inward/down the tunnel
- Collision detection between bullets, enemies, and player
- Score, lives, level number, and game-over screen
- Increasing difficulty each level
- Smooth animation using `requestAnimationFrame`
- Retro arcade sound effects using the Web Audio API
- No external assets; generate all geometry, colors, and sounds procedurally
- Clean, well-commented code

## Controls

- **Left/Right** or **A/D**: Move around the tunnel rim
- **Space**: Shoot down the tunnel
- **Enter**: Start or restart the game

## Enemy Types

- **Basic crawler**: Standard enemy that advances up a lane
- **Fast crawler**: Quicker enemy that pressures the player
- **Spiker**: Enemy that leaves a dangerous trail behind it

## Implementation Requirements

- Use Three.js for rendering
- Use `BufferGeometry` or `LineSegments` for the vector tunnel
- Use a perspective camera looking into the tunnel
- Use emissive/neon materials or line materials
- Make the game responsive to browser window size
- Put everything in one complete HTML file that can run locally in a browser

## Code Organization

Organize the code into these classes:

- `Game`
- `Player`
- `Tunnel`
- `Enemy`
- `Bullet`
- `InputManager`

## Visual Effects

Include simple but polished visual effects:

- Enemy explosions
- Screen shake on player hit
- Flashing tunnel on level completion

## Originality Constraint

Do not copy copyrighted assets, names, or exact level layouts. Create an original arcade shooter that captures the general feel of a fast neon vector tunnel shooter.
