# 🐽 Boop-A-Snoot

A cute, gentle take on whack-a-mole. Critters pop out of their burrows — tap or click each one for a boop! You get 30 seconds, and they get quicker as the round goes on.

**Play it:** https://rs-howell.github.io/boop-a-snoot/

## How to play

- Tap or click the **critter** itself when it pops up (not the burrow).
- The faster you boop, the more points: an instant boop is worth 100, a last-second one is worth 20.
- Missing a critter costs nothing — it only resets your streak. No penalties, just hearts.

## Features

- 30-second rounds with a 3×3 grid of burrows and 12 different critters
- Speed-based scoring, plus streak tracking
- Stats page: rounds played, total boops, best round, average round, best streak
- Critter collection that fills in as you boop each animal
- Sound effects (synthesized in the browser) with an on/off toggle
- Works with touch and mouse; no account, no typing

## Tech notes

- Single self-contained HTML file — vanilla HTML, CSS, and JavaScript, no build step, no external assets
- Sounds generated with the Web Audio API
- Best scores, stats, and sound preference saved in the browser's `localStorage` (on-device only; nothing is sent anywhere)
- Banner ads load only on approved hostnames (never during gameplay)

## Running locally

Open `index.html` in any modern browser.

## Deploying

Upload the file as `index.html` in a repo named `boop-a-snoot` and enable GitHub Pages (Settings → Pages → `main` / root).

## License

© RS Howell. All rights reserved.
