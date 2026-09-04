# Laser Engraving Quote Calculator — iPhone Web App

This package is ready to host as a small PWA (Progressive Web App).

## Files
- `index.html` — calculator
- `manifest.json` — app metadata
- `sw.js` — offline caching
- `icons/` — iPhone/PWA icons

## Recommended: GitHub Pages
1. Create a free GitHub account if needed.
2. Create a new repository, for example: `laser-quote-calculator`.
3. Upload the contents of this folder so `index.html` is at the repository root.
4. In GitHub, go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose the `main` branch and `/ (root)`, then save.
7. GitHub will give you a website link.

## Add to iPhone Home Screen
1. Open the hosted link in Safari.
2. Tap the Share button.
3. Tap **Add to Home Screen**.
4. Tap **Add**.

The calculator will then open like an app.

## Notes
- Saved product costs, artwork costs, and business settings use browser local storage.
- Offline caching works only after the site is hosted over HTTPS and opened at least once.
- If you change the app files later, update the cache version in `sw.js` (for example, `laser-quotes-v2`) before redeploying.
