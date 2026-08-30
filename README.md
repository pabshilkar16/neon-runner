# Neon Runner

A polished, dependency-free endless runner for desktop and mobile browsers. Race through a neon city, dodge four obstacle types, collect coins, and use shield, magnet, double-score, and speed-boost power-ups.

## Play locally

The simplest option is to double-click `index.html`. For the most reliable browser behavior, start a tiny local server from this folder:

```bash
python3 -m http.server 8000
```

Then visit <http://localhost:8000> in a browser.

## Controls

- **Desktop:** Space or Up Arrow to jump; P or Escape to pause.
- **Mobile:** Tap anywhere on the game area to jump.
- Use the on-screen buttons to pause or toggle sound.

Progress and the high score are stored in the browser with `localStorage`. No account, backend, build step, or paid service is needed.
