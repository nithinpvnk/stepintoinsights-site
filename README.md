# Step into Insights — public site (privacy / support / marketing)

Static pages for the App Store's required **Privacy Policy URL** and
**Support URL** (plus an optional **Marketing URL**). Self-contained
HTML, no build step.

| File | Use in App Store Connect |
|---|---|
| `privacy.html` | **Privacy Policy URL** (required) |
| `support.html` | **Support URL** (required) |
| `index.html`   | **Marketing URL** (optional) |

## Before publishing
Support email is already set to `stepinsightsfeedback@gmail.com` across
all three pages. (Swap it with a find-and-replace if it ever changes.)

## Publish on GitHub Pages (≈3 min)
Host these in a **separate, public** repo (do **not** make the app's
source repo public).

1. Create a new public repo, e.g. `stepintoinsights-site`.
2. Copy `index.html`, `privacy.html`, `support.html` into it and push.
3. Repo → **Settings → Pages** → Source: **Deploy from a branch** →
   Branch: `main` / `/root` → Save.
4. After a minute your URLs are live:
   - `https://nithinpvnk.github.io/stepintoinsights-site/privacy.html`
   - `https://nithinpvnk.github.io/stepintoinsights-site/support.html`
   - `https://nithinpvnk.github.io/stepintoinsights-site/` (marketing)
5. Paste those into App Store Connect → App Information / Version.

> A custom domain (e.g. `stepintoinsights.app`) can be added later in the
> Pages settings; the github.io URLs are fully acceptable for submission.
