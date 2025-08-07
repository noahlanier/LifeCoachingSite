# Integrated Faith — Catholic Life Coaching

A simple, responsive static site for a Catholic life coaching practice.

## Quick start

- Serve locally with any static server, e.g. Python:
  ```sh
  cd integrated-faith
  python3 -m http.server 8000
  ```
  Then open `http://localhost:8000`.

## Customize

- Update contact form action in `contact.html` to your Formspree endpoint.
- Replace Calendly links with your scheduling URL.
- Edit copy across pages to reflect your story and services.
- Swap the logo in `assets/img/logo.svg` if desired.

## Structure

- `index.html` — Home
- `about.html` — Mission and bio
- `coaching.html` — Offerings
- `testimonials.html` — Client stories
- `blog.html` — Resources placeholder
- `contact.html` — Contact and scheduling
- `assets/css/styles.css` — Styles
- `assets/js/main.js` — Small enhancements
- `assets/img/logo.svg` — Simple SVG logo

## Notes

- This site is static (no backend). For forms, use a service like Formspree or host on Netlify and enable forms.
- SEO basics included (meta description, sitemap, robots). Add analytics if needed.