# Expense Tracker

A personal budget tracker, built as a Progressive Web App (PWA).

## Files

| File | Purpose |
|------|---------|
| `index.html` | The main app (no personal data inside) |
| `manifest.json` | PWA metadata (name, icons, theme) |
| `sw.js` | Service worker for offline support |
| `budgetph-data.json` | **Your personal budget data** — import this after opening the app |

> ⚠️ **Do NOT commit `budgetph-data.json` to a public repo** if you want to keep your financial data private. Add it to `.gitignore` and import it manually each time, or keep the repo private.

---

## Deploying to GitHub Pages

1. Create a new GitHub repository (set to **Private** if you want your data safe)
2. Upload all files: `index.html`, `manifest.json`, `sw.js`
3. Go to **Settings → Pages → Source** → set branch to `main`, folder to `/ (root)`
4. GitHub will give you a URL like `https://yourusername.github.io/your-repo/`

---

## First-Time Setup

1. Open the app URL on your phone
2. You'll see a **Welcome** screen — tap **"Import budgetph-data.json"**
3. Select the `budgetph-data.json` file from your phone storage
4. Your expenses, installments, subscriptions, and income are loaded!

---

## Installing as a PWA (Add to Home Screen)

### Android (Chrome)
- Open the app URL in Chrome
- Tap the **"Install"** banner at the bottom, OR
- Tap the 3-dot menu → **"Add to Home screen"**

### iOS (Safari)
- Open the app URL in Safari
- Tap the **Share** button (box with arrow)
- Tap **"Add to Home Screen"**

---

## Icons (Optional)

The manifest references `icon-192.png` and `icon-512.png`. You can create simple icons using any image editor, or generate them at https://realfavicongenerator.net. Without icons, the app still works — it just won't have a custom icon on your home screen.

---

## Exporting Your Data

Go to **⚙️ Settings → Export Data** to download a fresh `.json` backup at any time.
