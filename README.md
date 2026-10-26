# zylocope.github.io

Personal portfolio of La Min Oo (Zyne): AI engineer and data scientist.
One static page: a Three.js particle field morphs through four shapes as you scroll
(wave → vortex → ring → starfield) behind the content.

## Before going live

- [ ] `img/headshot.jpg`: the formal headshot, square, about 600×600. Initials show until it exists.
- [ ] `resume.pdf`: export the "AI Engineer" tab of the resume doc as PDF. The Résumé button hides itself until it exists.
- [ ] After the first deploy: set `og:image` in `index.html` to an absolute URL.

## Deploy on GitHub Pages

1. On GitHub, create a **public** repo named exactly `Zylocope.github.io`.
2. In this folder:
   ```
   git init
   git add .
   git commit -m "Portfolio v1"
   git branch -M main
   git remote add origin https://github.com/Zylocope/Zylocope.github.io.git
   git push -u origin main
   ```
3. Repo → Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute it's live at **https://zylocope.github.io**.

`index-old.html` is the September 2026 version, kept for reference. Delete it whenever you like.
