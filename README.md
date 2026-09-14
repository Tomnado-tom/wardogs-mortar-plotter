# Wardogs Mortar Plotter

A single-page tool for computing heading and range between two Wardogs map
grid positions, for mortar fire missions.

Enter your position and the target's (Wardogs coordinates, where 1 grid unit
= 100 m), and it live-updates:

- **Heading** — compass bearing from you to the target, 0–360°, clockwise
  from north
- **Range** — straight-line distance in meters

It also lets you save named mortar firing spots and target positions in the
browser, so you don't have to retype coordinates you use often.

No build step, no dependencies — `docs/index.html` is the whole app.

## Running it

Open `docs/index.html` directly in a browser, or serve the repo's `docs/`
folder via GitHub Pages (Settings → Pages → Deploy from a branch → `main`,
folder `/docs`).
