# Codesentry

> The security layer for AI-built apps. Connect your GitHub repo, get a
> Security Score (0–100), and ship an auto-generated PR that fixes the
> vulnerabilities.

Codesentry is built for developers shipping fast with tools like Cursor,
Lovable, v0, Windsurf, and Bolt — where speed often outruns security review.
Point it at a repo, and it scans, scores, and patches.

## Features

- **Security Score (0–100)** — one glanceable number per repo
- **Auto-fix PRs** — vulnerabilities become a reviewable GitHub pull request
- **Interactive sandbox** — try a scan on a sample project before signing up
- **ROI calculator** — model savings vs. manual audits by team size
- **Privacy-first** — zero-retention RAM sandbox; your code is never used to train models

## Tech stack

- Static single-page site: HTML + CSS + vanilla JS (no build step required)
- Fonts: Fraunces, Inter, IBM Plex Mono (Google Fonts)

## Quick start

Clone and open — no dependencies needed:

```bash
git clone https://github.com/<your-org>/codesentry.git
cd codesentry
open index.html          # or just drag it into a browser
```

Or serve it locally:

```bash
npx serve .              # http://localhost:3000
```

## Deployment

Any static host works — Netlify, Vercel, Cloudflare Pages, or GitHub Pages.
No build command; publish directory is the repo root.

## Project structure

    codesentry/
├── index.html          # the landing page
├── assets/
│   ├── css/            # if/when you split styles out of <style>
│   ├── js/             # if/when you split the <script> out
│   └── img/            # logo, og-image, favicons
├── .gitignore
├── README.md
└── LICENSE             # optional — omit for all-rights-reserved

## Roadmap

- [ ] Split inline CSS/JS out of `index.html` into `assets/`
- [ ] Add OG image + favicons
- [ ] Wire the CTA to the real signup/waitlist
- [ ] Analytics + consent banner

## License

All rights reserved. See [LICENSE](./LICENSE). © 2026 Codesentry.
