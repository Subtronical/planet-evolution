# 🌌 Cosmic Federation

**An Interactive 3D Solar System & Galaxy Explorer**

A real-time WebGL journey from the Sun to Andromeda — built with Three.js, React, and Web Audio API. No build step. No npm install. Open in a browser and go.

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge)](https://cosmic-federation.vercel.app)

---

## ✨ Features

- **3D Solar System** — all 8 planets with real NASA/ESA textures, accurate orbits, 95+ moons
- **130-second Cinematic Journey** — automated zoom from the Sun to Andromeda with orchestrated music
- **Milky Way Galaxy** — procedural top-down view + NASA Spitzer artist concept image, YOU ARE HERE marker
- **Space Agency Intel** — NASA · ESA · ESO · APOD · SpaceX · Artemis · ISRO · JAXA · Rocket Lab · ULA tabs
- **Future Missions** — 30+ funded missions across 5 categories with budgets, launch dates, live links
- **95+ Moons** — full moon catalogs for Jupiter (95), Saturn (146), Uranus (28), Neptune (16), Pluto (5)
- **Voyager 1 & 2** — both probes rendered at correct positions past the heliopause
- **Light-time Distances** — every waypoint shows AU + light-minutes/hours/years
- **Procedural Synth Score** — E Phrygian analog synth synchronized to cinematic waypoints
- **Kuiper Belt · Heliosphere · Oort Cloud** — extended solar system regions with 3D overlays
- **Andromeda Galaxy** — in the galaxy cinematic with distance and local group context

---

## 🚀 Deploy on Vercel (2 minutes)

### Option A — GitHub → Vercel (recommended)

**Step 1: Push to GitHub**
1. Go to [github.com](https://github.com) → click **+** → **New repository**
2. Name it `cosmic-federation`
3. Set to **Public** → click **Create repository**
4. Click **"uploading an existing file"**
5. Drag and drop ALL files from this folder:
   - `index.html`
   - `vercel.json`
   - `netlify.toml`
   - `.gitignore`
   - `README.md`
6. Click **Commit changes** ✅

**Step 2: Deploy on Vercel**
1. Go to [vercel.com](https://vercel.com) → **Sign in with GitHub**
2. Click **Add New → Project**
3. Find `cosmic-federation` → click **Import**
4. Leave ALL settings as default (Framework: Other, Build Command: none)
5. Click **Deploy**
6. ✅ Live in ~30 seconds at `https://cosmic-federation.vercel.app`

> **Custom domain:** In Vercel dashboard → Settings → Domains → add your domain

---

### Option B — Vercel CLI (terminal)

```bash
npm i -g vercel
cd cosmic-federation-deploy
vercel --prod
```

---

## 🌐 Deploy on Netlify (1 minute — drag & drop, no account needed)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the **entire `cosmic-federation-deploy` folder** onto the page
3. ✅ Live instantly at a random URL like `https://cosmic-abc123.netlify.app`
4. Optional: claim it with a free Netlify account to get a custom URL

> **With account:** Netlify → Add new site → Import from Git → connect GitHub → deploy

---

## 🎮 Controls

| Action | Control |
|--------|---------|
| Rotate view | Click + drag |
| Zoom | Scroll wheel |
| Click planet/moon | Opens info panel |
| Space agency tabs | Top navigation bar |
| ▶ Play cinematic | Cinematic button |
| 🔇 Mute music | Mute button |

---

## 🏗 Architecture

Single self-contained HTML file — no build step, no dependencies to install.

| Technology | Usage |
|-----------|-------|
| **Three.js r128** | 3D WebGL rendering, planet meshes, orbit rings |
| **React 18** | UI components, panels, tabs (loaded via CDN) |
| **Web Audio API** | Procedural E Phrygian synth score |
| **Canvas 2D** | Overlay animations (Oort Cloud, galaxy, Milky Way) |
| **Solar System Scope** | CC-BY planet textures (2K resolution) |
| **NASA/ESA** | Milky Way image, Earth photo, mission data |

---

## 📡 What's in the Cinematic

| Time | Scene |
|------|-------|
| 0–7s | The Sun — G-type star · 73% Hydrogen · 4.6 billion years old |
| 7–15s | Inner planets — Mercury · Venus · Earth · Mars with light-time distances |
| 15–26s | Earth close-up — the only confirmed life in the universe |
| 26–31s | Gas giants — Jupiter · Saturn · Uranus · Neptune |
| 31–37s | Kuiper Belt — 30–50 AU · 4.5–7.5 light-hours · Pluto · Eris |
| 37–42s | Heliosphere — Voyager 1 (214 AU) & Voyager 2 (190 AU) |
| 42–47s | Oort Cloud — 2,000–100,000 AU · 0.03–1.58 light-years |
| 47–100s | Milky Way — NASA Spitzer image · YOU ARE HERE · arm labels · LMC · SMC |
| 100–110s | Our island universe — 2 trillion galaxies · Andromeda 2.537M light-years |

---

## 🖼 Image Credits

- **Planet textures:** [Solar System Scope](https://www.solarsystemscope.com/textures/) (CC BY 4.0)
- **Milky Way:** NASA/JPL-Caltech/R.Hurt (SSC-Caltech) · Spitzer Space Telescope · Artist Concept
- **Earth:** NASA Apollo 17 · "The Blue Marble" (public domain)
- **Andromeda:** NASA/ESA Hubble Space Telescope (public domain)

---

## 📄 License

MIT — free to use, modify, and deploy.

Built by Sid Sharma · Developed across 15+ AI-directed sessions · 2026
