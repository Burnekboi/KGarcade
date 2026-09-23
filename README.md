# Nico John Nantes — Game Studio (Official Website)

Official company / developer landing page for indie game studio **Nico John Nantes**. Showcases all
published games and their free, playable web builds, hosted on GitHub Pages. Pure HTML/CSS/JS — no
frameworks, no CDNs, 100% HTTPS.

## Files

| File            | Purpose                                              |
| --------------- | --------------------------------------------------- |
| `index.html`    | Studio landing page (hero, games, about, support)   |
| `privacy.html`  | Studio Privacy Policy (GDPR / UK GDPR / CCPA)       |
| `terms.html`    | Studio Terms of Service                             |
| `styles.css`    | Shared stylesheet (lightweight, dependency-free)     |

## Games & live URLs

All games are free and playable in the browser (opens in a new tab):

| Game             | Genre            | Play (GitHub Pages)                                        | TikTok Mini |
| ---------------- | ---------------- | ---------------------------------------------------------- | ----------- |
| **One More Tap** | Reflex arcade    | https://burnekboi.github.io/one-more-tap-web/              | Yes         |
| **NEON GRID**    | Bullet-hell      | https://burnekboi.github.io/neon-grid-web/                 | Yes         |
| **Dungeon Knights** | Action RPG/crawler | https://burnekboi.github.io/dungeon-knights-web/         | Yes         |

Site + game repos:

```
Burnekboi/one-more-tap-landing   <- this site
Burnekboi/one-more-tap-web       <- One More Tap web build
Burnekboi/neon-grid-web          <- NEON GRID web build
Burnekboi/dungeon-knights-web    <- Dungeon Knights web build
```

## Details used

- Studio / developer: **Nico John Nantes**
- Support email: `niconan.shaun1128@gmail.com`
- Legal scope: One More Tap, NEON GRID, Dungeon Knights

## Rebuilding a game web build

**Neon Grid (Cocos Creator 3.8.8):**
```
"C:\ProgramData\cocos\editors\Creator\3.8.8\CocosCreator.exe" --project "<game folder>" --build "platform=web-mobile;debug=false"
```
Copy `build/web-mobile/*` into the `neon-grid-web` repo, commit, push. Pages re-deploys.

**Dungeon Knights (Vite + React):**
```
npm install --legacy-peer-deps
npx vite build --base=./
```
Copy `dist/*` into the `dungeon-knights-web` repo, commit, push.

## Local preview

Open `index.html` in a browser, or run a static server:

```bash
npx serve .
```

## Re-deploying the site

After editing, commit and push to `main`:

```bash
git add .
git commit -m "update site"
git push
```

GitHub Pages re-deploys automatically.

## Editing legal content

All legal text lives in `privacy.html` and `terms.html`. When review or legislation changes, update
the "Effective Date" / "Last Updated" lines, then redeploy. Update studio name, developer name, or
support email, in all three HTML files.