# Bible Words Reader — Support

Public support site for the iOS app **Bible Words Reader**, served via GitHub
Pages. This repo exists only to host these pages — the app source lives in a
separate private repo.

- `index.html` — support home: what the app is, contact, FAQ, text sources.
  This is the **Support URL** on the App Store listing.
- `privacy.html` — privacy policy. This is the **Privacy Policy URL** on the
  App Store listing.

Both URLs must stay reachable. Apple checks them during review.

## Editing

Plain HTML plus `style.css` — no build step, no dependencies, no external
resources. Edit and push; GitHub Pages redeploys in about a minute.

## Setup

Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.
