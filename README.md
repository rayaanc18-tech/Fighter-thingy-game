# Brawl Arena

A single-file browser game. No build step, no dependencies.

## Play locally
Open `index.html` in a browser (or run `python3 -m http.server` and visit http://localhost:8000).

## Deploy on GitHub Pages
1. Create a new GitHub repo and push these files to the `main` branch.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute your game is live at `https://<your-username>.github.io/<repo-name>/`.

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Notes
- Progress is saved in the browser's `localStorage` (per device/browser).
- `.nojekyll` tells GitHub Pages to serve the files as-is.
