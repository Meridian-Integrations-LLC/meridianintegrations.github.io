# Meridian Integrations

Premium smart home automation marketing site — Vite, React, and Tailwind CSS. Dark luxury aesthetic with a live lighting control simulator.

## Prerequisites

Fedora already has Node via the `nodejs22` package (`node` / `npm` on the PATH). If a terminal says `npm: command not found`:

```bash
sudo dnf install nodejs22
```

## Start locally

In a terminal:

```bash
cd ~/nexus-smart-home
npm install
npm run dev
```

Do not type `run` by itself — the command is `npm run dev`.

If you are already inside `~/nexus-smart-home` (Cursor’s project terminal), skip the `cd` and just run `npm run dev`.

Then open the URL Vite prints (typically http://127.0.0.1:5173).

## Other commands

```bash
npm run build    # production build to dist/
npm run preview  # preview the production build
```

## Project structure

```
src/
  App.jsx
  index.css
  data/content.js
  components/
    Navbar.jsx
    Hero.jsx
    LightingSimulator.jsx
    Offerings.jsx
    ConsultationForm.jsx
    Footer.jsx
    Icons.jsx
```

The homepage includes sticky navigation, a hero with an interactive dimmer and scene-color picker, a six-card services grid, a consultation form, and a multi-column footer with `info@meridianintegrations.com` and `720-295-1164`.
