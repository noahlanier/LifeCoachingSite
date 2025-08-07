# Integrated Faith — Catholic Life Coaching

A simple, responsive static site.

- Live site: https://noahlanier.github.io/LifeCoachingSite/
- Deployment: GitHub Pages via GitHub Actions (auto-deploys from `integrated-faith/` on pushes to `main`).

## Local preview (optional)
If you want to preview locally, use any static server:

```sh
cd integrated-faith
python3 -m http.server 8000
# open http://localhost:8000
```

## Project structure
- `integrated-faith/` — Site source (HTML/CSS/JS)
  - See `integrated-faith/README.md` for customization notes
- `/.github/workflows/pages.yml` — Pages deploy workflow
