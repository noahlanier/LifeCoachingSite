# Integrated Faith — Catholic Life Coaching

A simple, responsive static site for a Catholic life coaching practice.

## Quick start (local preview)

- Start a local server from this folder and open the site:
  - Option A (Python):
    ```sh
    cd integrated-faith
    python3 -m http.server 8080
    ```
    Then open [http://localhost:8080](http://localhost:8080).
  - Option B (Node):
    ```sh
    cd integrated-faith
    npx --yes serve -s . --listen 8080
    ```
    Then open [http://localhost:8080](http://localhost:8080).

- Interactions to test:
  - Mobile navigation toggle
  - Call-to-action buttons (Calendly links)
  - Contact form submission (requires replacing the placeholder Formspree endpoint)

## Make it publicly accessible

- Netlify (fastest)
  1) Drag-and-drop the `integrated-faith` folder to Netlify deploys, or connect a repo
  2) Publish directory: `integrated-faith`
  3) Netlify will give you a live URL instantly

- GitHub Pages
  1) Commit this folder to a GitHub repo
  2) In repo Settings → Pages, set Source to `main` and folder `/ (root)`
  3) Your site will be live at `https://<your-username>.github.io/<repo>/`

- Vercel
  1) Import the repo in Vercel
  2) Output directory: `integrated-faith`
  3) Deploy to get a live URL

## Customize

- Update contact form action in `contact.html` to your Formspree endpoint
  - Replace `https://formspree.io/f/your-form-id` with your form ID
- Replace Calendly links with your scheduling URL
- Edit copy across pages to reflect your story and services
- Swap or update the logo in `assets/img/logo.svg`

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
- `assets/img/og-cover.svg` — Social share image (Open Graph)
- `sitemap.xml`, `robots.txt` — Basic SEO

## Notes

- This site is static (no backend). For forms, use a service like Formspree or host on Netlify Forms
- Basic SEO included (meta description, sitemap, robots). Add analytics if needed