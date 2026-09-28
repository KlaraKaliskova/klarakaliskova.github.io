# KlaraKaliskova.github.io

Personal webpage of Klára Kalíšková, built as a static site for GitHub Pages.

Content is based on the original site at https://home.cerge-ei.cz/kaliskova/, redesigned with a modern responsive layout while keeping all text, navigation tabs, and documents (CV, links to publications and policy briefs).

## Structure

- `index.html` – Home
- `cv.html` – CV (with embedded PDF)
- `research.html` – Research (work in progress, publications, policy briefs)
- `teaching.html` – Teaching
- `assets/css/style.css` – stylesheet
- `assets/img/` – photo
- `assets/files/` – CV PDF

## Publishing on GitHub Pages

1. Create a new public repository under the `KlaraKaliskova` account named exactly `KlaraKaliskova.github.io`.
2. Push this repository to it:
   ```
   git remote add origin https://github.com/KlaraKaliskova/KlaraKaliskova.github.io.git
   git push -u origin main
   ```
3. In the repo's Settings → Pages, source should already default to the `main` branch root — the site will appear at `https://klarakaliskova.github.io/` within a few minutes.
