# Muhammed Hesham — Portfolio

My personal portfolio website: a single, hand-built `index.html` — no frameworks, no build step, no external requests.

## Publish it with GitHub Pages (free)

1. Merge this branch into `main`.
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://muhammedhesham136.github.io/GMC/`.

Tip: rename this repository to `muhammedhesham136.github.io` and the site will live at that cleaner root URL instead.

## Edit the content

Everything lives in `index.html`. The text is plain HTML — search for the section you want:

- **Name / title / tagline** — in the `<!-- HERO -->` section.
- **About paragraphs** — in the `<!-- ABOUT -->` section.
- **Skills** — the `<li>` chips inside the `<!-- SKILLS -->` section.
- **Projects** — each `<article class="project-card">` in `<!-- PROJECTS -->`. Copy one to add a new project. When a project has its own repo, add a link inside its `project-meta` block.
- **Email / GitHub links** — search for `muhammedhesham1000@gmail.com` and `github.com/muhammedhesham136`.
- **Colors** — the `:root { … }` variables at the top of the `<style>` block.

Open `index.html` in a browser to preview any change instantly — no tooling needed.
