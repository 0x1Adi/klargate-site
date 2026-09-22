# klargate.com

The Klargate website. Public on purpose: this repo holds only what is meant to be
served. Strategy, pricing and sales material live in the private `klargate-marketing`
repo and must never be added here.

| Path | Page |
| --- | --- |
| `/` | `index.html` — Klargate, the company. Klarion now, provmcp coming soon |
| `/klarion` | `klarion.html` — the Klarion product page |
| `/evilsnooze/` | `evilsnooze/` — EvilSnooze (iPhone app by Aditya Tiwari; hosted here, not a Klargate product): about, `support`, `privacy`. The App Store listing and the app link to `support` and `privacy`: never move or rename them without updating the app. The privacy page mirrors `docs/privacy-policy.md` in the evilsnooze repo |

`CNAME` holds the custom domain. `.nojekyll` stops GitHub Pages running the files
through Jekyll.

Served by GitHub Pages from `main`. Push to `main` deploys.
