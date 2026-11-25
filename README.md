# ICON — 3D scroll landing page

An interactive, scroll-snapped 3D product page for the Tyent ICON hydrogen water ionizer, built with Three.js. Each step walks through one part of the machine: controls, inlet, filtration, the dual cell, electrolysis, dispensing and smart care.

## Run locally

```
node serve.mjs
```

Then open http://localhost:5188. Any static file server works; the page is a single `index.html` plus `assets/`.

## Controls

- Scroll, swipe, arrow keys or Page Up/Down to step between phases
- `#0`–`#8` in the URL jumps straight to a phase
- On phones, tap the bottom sheet (or "Details") to expand the info

## Files

- `index.html` — the whole page (Three.js model, phases, UI)
- `assets/bg.png` — backdrop
- `assets/intro.mp4`, `assets/intro_9x16.mp4` — intro films (16:9 and 9:16)
- `serve.mjs` — tiny static server for local preview
- `research.md` — product research notes
