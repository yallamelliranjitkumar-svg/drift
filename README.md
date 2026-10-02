# Drift

A ten-minute descent through the ocean's four zones, from the surface to the heart of the deep at 6,000 m.

- Meet 20 real species at the depths where they live, from whale sharks to bigfin squid
- Unlock a fact about Earth's oceans every 200 m
- Collect light, dodge shadow eels, and catch three power-ups
- Build a field guide covering the species you've met, the depth log, and the five oceans and notable seas

## Play

Open `index.html` in any modern browser. There is no build step and nothing to install.

**Phone:** drag to swim, tap to pulse light.
**Computer:** move the mouse (or arrow keys / WASD) to swim, click or Space to pulse. P pauses, G opens the field guide, M mutes.

Progress (field guide, saved dive, fastest time) is stored in the browser's local storage.

## Tech

A single self-contained HTML file: HTML5 Canvas 2D for rendering, the Web Audio API for generated sound, and plain JavaScript. The only external requests are Google Fonts.

## Deploy

It's a static site, so any static host works. On Vercel: import the repository, choose the **Other** framework preset, leave the build command empty and the output directory as the project root.
