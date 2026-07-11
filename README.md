# Aditya Singh — Personal Website

Personal academic website of **Aditya Singh**, PhD student in the Department of Chemistry, IIT Delhi.

Live site (after deploying): **https://aditya-mat.github.io**

## Structure
- `index.html` — home (about, education, awards, news, research interests)
- `cv.html` — full CV + downloadable PDF (`assets/Aditya_Singh_CV.pdf`)
- `experience.html` — research experience, leadership, conferences, coursework
- `blog.html` — blog posts (edit the `<article>` blocks to add posts)
- `photography.html` — photo gallery (drop images in `images/photography/`)
- `assets/` — CSS and JS · `images/` — photo and logos

Plain HTML/CSS (Bootstrap 4) — no build step. `.nojekyll` keeps GitHub Pages serving files as-is.

## Editing
- Profile photo: replace `images/profile.jpg`
- Update the CV PDF: replace `assets/Aditya_Singh_CV.pdf`
- Add photos: put files in `images/photography/` and point the `src` in `photography.html` at them

## Deploy (GitHub Pages)
1. Create a repo named `aditya-mat.github.io` on GitHub.
2. Push this folder to it.
3. Enable Pages (Settings → Pages → deploy from `main` branch).

---
Design adapted from an open-source academic homepage template (MIT-licensed).
