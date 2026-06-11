# Coulton Ventures

Static single-page site for Coulton Ventures, hosted at <https://coultonventures.makeacompany.ai>.

## What's here

- `index.html` — the entire site. Zero build step, zero deps beyond Google Fonts (loaded via CDN).
- `CNAME` — custom domain for GitHub Pages.

## Porting to your own host

Drop `index.html` into any static host (Netlify, Vercel, S3 + CloudFront, your existing setup). No build pipeline required.

If you want to swap the domain at the top of the file:

1. Edit the `<link rel="canonical">`, `og:url`, and JSON-LD `url` in the `<head>` to your final domain.
2. Update the `CNAME` (if using GitHub Pages) or your host's domain settings.

## Stack

- Single static HTML file, inline CSS
- Cormorant Garamond + Inter (Google Fonts)
- Schema.org Organization JSON-LD for SEO
- OG / Twitter card meta for social previews
- Fully responsive (mobile-first), prefers-reduced-motion respected
