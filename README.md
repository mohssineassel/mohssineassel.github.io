# Portfolio

Personal portfolio site, hosted for free on GitHub Pages. Plain HTML and CSS: no build step.

## Before publishing

- [x] LinkedIn URL set (`linkedin.com/in/mohssine-assel`).
- [x] CV added as `cv.pdf` (the "Download CV" button links to it).
- [ ] Add GitHub links for *RAG Evaluation Framework* and *Marathon Photo Retrieval* if they're public.
- [ ] Record a 1–2 min SciRAG demo, save it as `assets/scirag-demo.mp4`
      (keep it under ~20 MB), and uncomment the `<video>` block in `index.html`.

## Deploy to GitHub Pages

1. On GitHub, create a **public** repo named exactly `mohssineassel.github.io`.
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/mohssineassel/mohssineassel.github.io.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Source: Deploy from a branch → `main` / root**.
4. After a minute the site is live at **https://mohssineassel.github.io**.

Every later `git push` updates the site.

## Preview locally

Open `index.html` in a browser, or run `python -m http.server` and go to http://localhost:8000.
