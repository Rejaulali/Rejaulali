# Rejaul Research — academic portfolio v2

A six-page, responsive, GitHub Pages-compatible static website. No build process or paid hosting needed.

## Preview
Open `index.html` in a browser. For publications loaded from JSON, use a local server (`python -m http.server 8000`) and visit http://localhost:8000, or view the published site on GitHub Pages.

## Publish free on GitHub Pages
1. Create a public GitHub repository named `YOURUSERNAME.github.io` (replace YOURUSERNAME with your GitHub username).
2. Upload **the contents** of this folder, including `index.html`, the other HTML files, `assets/`, and `data/`, to the repository root. Do not upload only the ZIP.
3. Open Settings → Pages → Build and deployment → Deploy from a branch; select `main` and `/(root)`; save.
4. Visit `https://YOURUSERNAME.github.io` after deployment finishes.

## Update content
- Home and research: edit `index.html` and `research.html`.
- Publications: edit `data/publications.json`. Example:
  `[{"year":"2026","title":"Exact paper title","authors":"A. Author, B. Author","venue":"Journal or conference","url":"https://doi.org/your-doi"}]`
  Use actual verified records only.
- Gallery: replace abstract inline SVG placeholders in `gallery.html` with your own `<img src="assets/figure-name.webp" alt="...">` and meaningful captions.
- CV: place a public-safe PDF at `assets/Rejaul_CV.pdf`, then replace the 'Request my CV' button in `cv.html` with `<a class="btn" href="assets/Rejaul_CV.pdf" download>Download CV</a>`.
- Contact: add your actual LinkedIn, Scholar, ORCID, and email links in `contact.html`.
- Colors/layout: `assets/style.css`; navigation/filters/publication loading: `assets/main.js`.

## Notes
Research illustrations are intentionally conceptual and must not be presented as experimental results. No DOI, affiliation beyond known BITS Pilani information, or professional profile URLs were invented. The site supports keyboard navigation, responsive layouts, and reduced-motion preferences. Google Fonts requires internet; fallback fonts are included.
