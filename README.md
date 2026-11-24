# [prtx.github.io](https://prtx.github.io)

Personal site of Pratik Shrestha. Plain HTML + CSS, no build step.

- `index.html` — all content: hero, About me, Research, Publications, Notes (and a dark-mode-only `/tmp`)
- `assets/css/site.css` — styles; light by default, dark via the toggle
- `assets/css/fontawesome-all.min.css`, `assets/webfonts/` — icons
- `assets/images/` — portraits (light and dark) and the EDA-Learn diagram

To add a note: in `index.html`, find the commented-out `<article class="thought">` template in the Notes section.

Preview locally: `python3 -m http.server` and open http://localhost:8000.
