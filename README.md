#Rent Manager

This repository contains a single-file static app (`index.html`) for managing driver daily entries (rent, fuel, extra costs) and viewing charts.

## How to publish with GitHub Pages

### Option A — Create a new repository and upload files (GitHub web)
1. Go to https://github.com and create a new repository (e.g. `driver-dashboard`).
2. Upload `index.html`, `README.md`, `LICENSE`, and `.nojekyll` using the "Add file" → "Upload files" button.
3. After files are uploaded, go to **Settings → Pages** (or **Settings → Pages** in the left sidebar).
4. Under **Build and deployment**, select **Deploy from a branch** (or similar). Choose branch `main` (or `master`) and folder `/ (root)`.
5. Save — your site will publish at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

### Option B — Using Git (recommended)
```bash
git init
git add .
git commit -m "Initial commit — driver dashboard"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
Then enable GitHub Pages in repository **Settings → Pages** and select branch `main` and folder `/ (root)`.

## Notes
- `index.html` uses Chart.js from CDN. Internet is required for charts to load.
- If you want a custom domain, add a `CNAME` file with your domain.
- `.nojekyll` is provided so GitHub Pages serves files from root without Jekyll processing.
