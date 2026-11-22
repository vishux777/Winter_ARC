# HYBRID — Body Recomposition Planner

A mobile-first, single-file fitness planner: 12 weekly sessions (AM and PM, Tuesday rest), nutrition targets, cardio and recovery guidance. Plain HTML, CSS and vanilla JavaScript. No backend, no framework, no build step, no API keys.

## Files

- `index.html` — the whole site
- `README.md` — this file

## Deploy on GitHub Pages

### Option A — Browser only

1. Sign in at [github.com](https://github.com) and click **New repository**.
2. Name it (for example `hybrid-planner`), set it to **Public**, and click **Create repository**.
3. Click **uploading an existing file**, drag in `index.html` (and `README.md`), then **Commit changes**.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
6. Choose branch **main** and folder **/ (root)**, then click **Save**.
7. Wait 1–2 minutes. Your site will be live at:
   `https://<your-username>.github.io/<repository-name>/`

### Option B — Git command line

```bash
git init
git add index.html README.md
git commit -m "Add HYBRID planner"
git branch -M main
git remote add origin https://github.com/<your-username>/<repository-name>.git
git push -u origin main
```

Then enable Pages as in steps 4–7 above.

## Notes

- `index.html` must be in the root of the repository.
- Progress is saved with `localStorage` in the browser on that device. It does not sync between devices, and clearing site data resets it.
- To use it like an app on your phone, open the site and choose **Add to Home Screen**.
- To test locally, open `index.html` in a browser, or run `python3 -m http.server` in the folder.
- This is general fitness information, not medical advice.
