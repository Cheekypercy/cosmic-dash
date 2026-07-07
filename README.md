# 🚀 Cosmic Dash

A pixel-art endless runner — a cool space-astronaut twist on the Chrome offline dino game.
Built as a **single `index.html`** with vanilla JS + Canvas. No build step, no dependencies,
mobile-first. Just open it and play.

![pixel art](https://img.shields.io/badge/style-pixel%20art-23e0ff) ![no deps](https://img.shields.io/badge/dependencies-none-ff7a2d)

## ▶️ Play

**Live link:** https://cheekypercy.github.io/cheekypercy/  *(after Pages is enabled — see below)*

Or run it locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## 🎮 How to play

| Action | Touch (phone) | Keyboard |
| --- | --- | --- |
| Jump | Tap anywhere | `Space` / `↑` / `W` |
| Jetpack hover | Hold (uses fuel) | Hold the key |
| Duck / fast-fall | Swipe down | `↓` / `S` |
| Start / Retry | Tap the screen | Any jump key |

- Jump over **asteroids**, duck under flying **satellites**.
- **Hold to hover** with your jetpack — watch the little fuel bar above your head;
  it drains while thrusting and refills on the ground.
- Grab **weapon pickups** (BLASTER / PLASMA) — they **auto-fire at asteroids ahead**
  so you can blast through instead of dodging, but ammo is limited.
- Snag **star coins**, chain **near-miss combos**, and collect **power-ups**:
  🛡️ shield, ⏳ slow-mo, ⏫ double-jump.
- The world shifts **biome every 500m** (Deep Space → Mars → Ice World → Asteroid Belt → Toxic Nebula).
- Unlock new **astronaut skins** as your best score climbs (cycle them on the start screen).
- Your **high score** and unlocks are saved on your device (`localStorage`).
- Tap **SND** (top-right) to mute/unmute the retro blips.

## ✨ Features

- Crunchy pixel-art rendering (low-res buffer upscaled with `image-rendering: pixelated`).
- Hand-drawn sprites: animated astronaut, asteroids, satellites, pickups.
- Jetpack hover with a regenerating fuel gauge.
- Collectible weapons with limited ammo + smart auto-targeting.
- Coins, near-miss combo multiplier, and three power-ups.
- Five biomes that recolour the sky, ground, and asteroids every 500m.
- Unlockable skins gated by best score.
- Parallax starfield, drifting ringed planet, CRT scanlines, Web Audio SFX, and haptics.
- Retro **Press Start 2P** HUD font.

> Coming in Phase 2: mini-bosses & bosses every 1000m (escalating difficulty), with
> power-ups and weapons doubling as combat tools.

## 🌐 Enable the phone link (one-time)

GitHub Pages just needs to be switched on once:

1. Go to the repo on GitHub → **Settings** → **Pages**.
2. Under **Source**, choose **Deploy from a branch**.
3. Branch: `claude/session-TfyZL`, folder: `/ (root)` → **Save**.
4. Wait ~1 minute, then open **https://cheekypercy.github.io/cheekypercy/** on your phone.

> Prefer a permanent link? Merge this branch into your default branch and point Pages at that instead.
