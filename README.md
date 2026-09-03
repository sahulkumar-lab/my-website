# K2Kumar-IT — Cybersecurity Course

A single-page animated landing site for a cybersecurity course, built with plain HTML, CSS, and JavaScript (no build step, no dependencies).

## Features
- Animated matrix-style background (canvas)
- Glitch-text hero headline
- Typing terminal animation
- Scroll-reveal course modules
- Fully responsive, respects `prefers-reduced-motion`

## Run locally
Just open `index.html` in a browser — no server or build step needed.

## Deploy with GitHub Pages
1. Push this repo to GitHub (see steps below).
2. Go to **Settings → Pages** in your repo.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit: K2Kumar-IT cybersecurity course site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
