# anvo-website

Static landing site for [anvo.io](https://anvo.io). Deployed via Cloudflare Pages directly from this repo — no build step.

## Local preview

Any static file server works. Examples:

```
python3 -m http.server 8000
# or
npx serve .
```

Then open http://localhost:8000.

## Deploy

Cloudflare Pages is configured to deploy the repository root on every push to `main`. No build command, no framework detection needed.

## Files

- `index.html` — landing page
- `404.html` — 404 fallback
- `favicon.svg` — inline-SVG favicon
- `_headers` — Cloudflare Pages security headers (CSP, HSTS, etc.)
