# Dirtbag Soap Co.

Static landing page for **Dirtbag Soap Co.** — lavender liquid castile soap concentrate made in North Hollywood, CA.

- **Slogan:** Put it on everything. And everyone.
- **Primary CTA:** Shop on TikTok ([`@dirtbagsoapco`](https://www.tiktok.com/@dirtbagsoapco))

## Structure

- `index.html` — Semantic single-page site with Open Graph and meta tags (zero analytics)
- `styles.css` — Responsive styles for mobile (390px) and desktop (1280px+)
- `assets/og-image.png` — 1200×630 Open Graph preview image
- `assets/favicon.svg` — Site icon
- `scripts/verify.mjs` — Local static build & verification check

## Local verification

```bash
npm run build
```

Serve locally with any static server, e.g.:

```bash
npx serve .
# or
python3 -m http.server 4173
```
