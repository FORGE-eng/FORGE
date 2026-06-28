# FORGE — A Field Guide to Your Own Mind

A self-mastery PWA with 46 concepts, a daily concept + task, and a personal journal.

## Deploy to GitHub Pages

1. Create a **public** GitHub repo (or use an existing one)
2. Upload the entire contents of this folder to the repo root
3. Go to **Settings → Pages → Branch: main → / (root)** → Save
4. Your app will be live at `https://yourusername.github.io/reponame`
5. On Android: open in Chrome → three-dot menu → **Add to Home Screen**
6. On iOS: open in Safari → Share → **Add to Home Screen**

## Convert to APK (optional)

1. Deploy to GitHub Pages first
2. Go to [pwabuilder.com](https://pwabuilder.com)
3. Enter your GitHub Pages URL
4. Click **Build** → **Android** → Download APK

## Files

```
index.html        ← the entire app
manifest.json     ← PWA config (name, icons, colors)
sw.js             ← service worker (offline support)
icons/            ← app icons in all required sizes
.nojekyll         ← tells GitHub Pages not to process as Jekyll
```
