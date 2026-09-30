# Abdullah Al Farhad — Academic Portfolio

A responsive static academic portfolio designed for GitHub Pages.

## Structure
- `index.html` — main site
- `assets/styles.css` — visual design
- `assets/script.js` — navigation and scroll reveal
- `assets/profile.png` — profile photo extracted from the supplied CV
- `assets/Abdullah_Al_Farhad_CV.pdf` — downloadable CV

## Local preview
Open `index.html` directly in a browser, or run a local HTTP server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages
1. Create a repository named `YOUR-USERNAME.github.io`.
2. Upload the **contents** of this folder to the repository root.
3. In GitHub: Settings → Pages → Build and deployment → Deploy from a branch.
4. Select `main` and `/ (root)`.
5. The site will be published at `https://YOUR-USERNAME.github.io/`.

## Before publishing
Add your GitHub, Google Scholar, LinkedIn, ORCID and publication DOI links when available. The current build deliberately avoids inventing links that were not present in the supplied CV.
