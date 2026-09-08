# 🐢 Build a Stacking Game — a free DevShare course

An interactive, self-contained course that teaches browser game development by
building a real arcade game. **10 chapters, 9 live code editors, a playable game at the end.**

**▶ Live course:** https://devkancheti4-design.github.io/devshare-stacking-game/

## What it teaches

| Chapter | Topic |
|---|---|
| 1 | Meet the game — input → update → draw |
| 2 | Your first canvas — shapes, colours, coordinates |
| 3 | The game loop — `requestAnimationFrame` |
| 4 | Drawing characters from circles and rectangles |
| 5 | Gravity and bouncing — position, velocity, acceleration |
| 6 | Input that works on mouse, touch and keyboard |
| 7 | Stacking and collision — rectangle overlap maths |
| 8 | Scoring, perfect landings and combos |
| 9 | Juice — particle bursts and screen shake |
| 10 | The complete game + deploying it |

## Features

- **Live editors** — every example opens in a full-screen editor with instant preview,
  sandboxed so learner code can't break the page
- **Quizzes** that mark chapters complete, with progress saved in `localStorage`
- **Fully responsive** — works on a phone, no login, no build step
- **Zero dependencies** — one `index.html` file, plain HTML/CSS/JavaScript

## Tech

Vanilla JavaScript, HTML5 Canvas, CSS Grid/Flexbox. No frameworks, no bundler.
The final game implements a fixed-timestep-free `requestAnimationFrame` loop with
gravity, AABB overlap collision, combo scoring, a particle system and screen shake.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## About DevShare

DevShare sends subscribers a brand-new interactive course like this one every week,
on topics they request. Courses start **October 1, 2026**.

- Site: https://devshare-com.netlify.app
- Another free course: [Birthday Surprise Website](https://devshare-640.netlify.app)
- Pre-book: WhatsApp **"PREBOOK"** to **93986 16191**
