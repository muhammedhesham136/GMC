# Muhammed Hesham — Portfolio & Demos

My personal portfolio website plus client-style demo sites I build to showcase my work. Hand-written HTML/CSS/JS — no frameworks, no build step.

## Structure

| Path | What it is |
|---|---|
| `index.html` | My developer portfolio (dark "midnight glass" design) |
| `demos/dental-clinic/` | **Lumina Dental Studio** — fictional dental clinic demo: Three.js WebGL hero, crossfading background videos, before/after gallery, booking form |
| `assets/` | Shared images (demo preview thumbnails) |

Live site: `https://muhammedhesham136.github.io/GMC/` · demo: `https://muhammedhesham136.github.io/GMC/demos/dental-clinic/`

## Publish with GitHub Pages

1. Merge this branch into `main`.
2. **Settings → Pages** → Source: *Deploy from a branch* → `main` / `/ (root)` → Save.
3. The site goes live at the URLs above within a minute of each merge.

## Add a new demo

1. Create a folder `demos/<demo-name>/` with its own `index.html` (keep it self-contained).
2. Add a preview screenshot to `assets/`.
3. Copy the "featured card" block in `index.html` (search for `featured-card`) or a `project-card` block, and point it at the new demo folder.

## Edit content

Everything is plain HTML. In `index.html` search for the section you need: hero text, About paragraphs, `chips` (skills), `project-card` (projects), or your email/GitHub links. In the demo, all clinic copy lives in `demos/dental-clinic/index.html`.

Note: `demos/dental-clinic` is a fictional business — its branding, reviews, and contact details are invented for portfolio purposes, and the page says so in its footer.
