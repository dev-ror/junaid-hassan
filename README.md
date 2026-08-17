# Junaid Hassan — Portfolio

A single-page, static portfolio site. No build step, no framework — plain
HTML/CSS/JS, so it deploys anywhere in minutes.

## Files
- `index.html` — the page
- `styles.css` — all styles
- `script.js` — mobile nav toggle + footer year
- `robots.txt` — crawler rules (search engines + AI bots)
- `sitemap.xml` — sitemap
- `llms.txt` — plain-text summary for AI assistants/LLMs (emerging `llms.txt` standard)

## Before you deploy — fill these in

1. **Domain.** Replace `https://junaidhassan.dev/` throughout `index.html`
   (canonical, Open Graph, Twitter, JSON-LD), `robots.txt`, and
   `sitemap.xml` with your real domain or GitHub Pages URL
   (e.g. `https://<username>.github.io/`).
2. **Scale numbers.** In the "What I Build" section of `index.html`, six
   items (Mailbot, Pushbot, WhatsApp Integration, Feed App, Sort App,
   Centralized SSO) have a highlighted placeholder like
   `<mark class="fill">add: stores served / emails sent per month</mark>`.
   Replace each with a real, honest figure — search `class="fill"` in
   `index.html` to find all six. Once filled in, you can drop the
   `class="fill"` styling if you'd rather they look like plain text.
3. **Open Graph image (optional).** `og-image.png` is referenced but not
   included — add a 1200×630 image at the site root, or remove the two
   `og:image` / `twitter:image` tags if you'd rather skip it.

## Deploy to GitHub Pages

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

Then in the repo: **Settings → Pages → Source → Deploy from branch → main /
(root)**. The site will be live at `https://<username>.github.io/<repo>/`
(or your custom domain, if you add a `CNAME` file and configure DNS).

## Local preview

Just open `index.html` in a browser, or run a tiny local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
