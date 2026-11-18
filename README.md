# 90-Day Lean Plan

A training and meal plan that installs on your phone and works offline.

## Publish (one time)
1. Push this folder to a GitHub repo.
2. Settings → Pages → Source: **Deploy from a branch** → `main` / `(root)` → Save.
3. Open `https://<username>.github.io/<repo>/` on your phone.
4. Add it to your home screen: Chrome → ⋮ → **Install app** (Android), or Safari → Share → **Add to Home Screen** (iPhone).

## Updating
Edit `index.html`, commit and push. The phone gets the new page the next time you open it online.
If you change fonts or icons, also bump `VERSION` in `sw.js`.

Ticks (exercises, meals, start date) are saved on the phone only.
