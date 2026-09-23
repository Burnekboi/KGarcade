# One More Tap — Official Landing Page

Clean, professional, mobile-responsive developer landing page for the **One More Tap** TikTok Mini Game submission, served 100% over HTTPS.

## Files

| File          | Purpose                                              |
| ------------- | ---------------------------------------------------- |
| `index.html`  | Landing page (hero, features, game modes, support)   |
| `privacy.html`| Privacy Policy (GDPR / UK GDPR / CCPA compliant)     |
| `terms.html`  | Terms of Service                                     |
| `styles.css`  | Shared stylesheet (lightweight, dependency-free)     |

## Details used

- Developer: **Nico John Nantes**
- Game title: **One More Tap** (arcade reflex H5 mini-game)
- Support email: `niconan.shaun1128@gmail.com`

## Local preview

Open `index.html` in a browser, or run a static server:

```bash
npx serve .
```

## Live URL

Served via GitHub Pages:

- Home: `https://Burnekboi.github.io/one-more-tap-landing/`
- Privacy: `https://Burnekboi.github.io/one-more-tap-landing/privacy.html`
- Terms: `https://Burnekboi.github.io/one-more-tap-landing/terms.html`

Register these URLs plus the support email in the TikTok Developer Portal when configuring the Mini Game app.

## Re-deploying

After editing, commit and push to `main`:

```bash
git add .
git commit -m "update landing page"
git push
```

GitHub Pages re-deploys automatically.

## Editing legal content

All legal text lives in `privacy.html` and `terms.html`. When review or legislation changes, update the
"Effective Date" / "Last Updated" lines and the corresponding entry, then redeploy. If your app name,
developer name, or support email changes, update it in `index.html`, `privacy.html`, and `terms.html`.