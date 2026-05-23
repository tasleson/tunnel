# Rimfire

Rimfire is a browser arcade game inspired by early vector tunnel shooters. It is built with Three.js, procedural wireframe geometry, and Web Audio API sound effects.

## TL;DR I just wanna play it now!

https://tasleson.github.io/tunnel/game.html

## Play locally

Open `index.html` through a local web server to view this README and play the game in an embedded window.

```sh
python3 -m http.server 8087
```

Then visit:

```text
http://127.0.0.1:8087/
```

You can also open `game.html` directly through the same server for a full-window game view.

## Controls

- `Enter`: start or restart
- `Left` / `Right` or `A` / `D`: move around the rim
- Mouse wheel: move one rim division per wheel click
- `Space`: fire down the tunnel

## Gameplay

- Shoot crawlers before they reach the rim.
- Enemies that reach the rim orbit around it.
- Green rim markers show segments where colliding with a rim enemy destroys it.
- Red rim markers show segments where colliding with a rim enemy damages you.
- If you stay on one rim segment too long, the safe and dangerous rim markers can rotate.
- Clearing a level warps you down the tunnel into the next procedurally generated level.

## Features

- Procedural randomized vector tunnel
- Three enemy types: basic crawler, fast crawler, and spiker
- Player bullets, enemy trails, collisions, score, lives, levels, and game over state
- Level-clear tunnel warp
- Enemy explosions, screen shake, flashing tunnel effects
- Procedural arcade sounds with Web Audio API
- No image or audio assets

## GitHub Pages

For GitHub Pages, publish the repository root. `index.html` is the project page and embeds `game.html` in a playable frame.
