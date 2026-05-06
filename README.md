# DJM Creative

Marketing agency website for DJM Creative — a Minneapolis-based marketing agency helping Twin Cities businesses grow through SEO, brand identity, web design, and content marketing.

**Live site:** [djm-creative.com](https://djm-creative.com)

---

## About

DJM Creative is a full-service marketing agency serving small and mid-sized businesses across Minneapolis, Saint Paul, and the broader Twin Cities metro. Services include:

- SEO & AI Search optimization
- Brand identity & strategy
- Web design & development
- Content & copywriting
- Paid media (Google Ads, Meta Ads)
- Social media marketing
- Email marketing & CRM

---

## Tech

Static single-page site built with vanilla HTML and CSS — no build step, no framework, no dependencies. Hosted on GitHub Pages.

- Semantic HTML5
- Custom CSS (no framework)
- JSON-LD structured data for local SEO
- Google Fonts: Archivo, Inter, JetBrains Mono
- Fully responsive

---

## Project structure

```
.
├── index.html          # Main page
├── assets/
│   ├── logo-dark.png   # Logo (light gray on dark)
│   └── logo-light.png  # Logo (dark on light)
└── README.md
```

---

## Local development

No build tools required. To preview locally:

1. Clone or download the repo
2. Open `index.html` directly in a browser, or run a quick local server:

```bash
# Python 3
python -m http.server 8000

# Node
npx serve
```

Then visit `http://localhost:8000`.

---

## Deployment

Deployed via GitHub Pages from the `main` branch root. Any push to `main` triggers a redeploy automatically (1–2 minute propagation).

To enable Pages on a fork or new clone:
1. Go to **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `(root)`
4. Save

---

## Custom domain

The site uses a custom domain configured via:
- A `CNAME` file at the repo root containing `djm-creative.com`
- DNS A records pointing to GitHub Pages IPs (`185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`)
- A `www` CNAME record pointing to `djmcreative.github.io`

---

## Contact

Dakota — [dakota@djm-creative.com](mailto:dakota@djm-creative.com)

---

© 2026 DJM Creative · Minneapolis, MN
