# dilina-r.github.io

Personal website of Dilina Rajapakse. Live at **https://dilina-r.github.io**

## Files
- `index.html` — the whole website (edit text directly)
- `cv.pdf` — the CV linked by the "Download CV" button (replace this file to update it)
- `photo.jpg` — optional profile photo (see below)

## Publish on GitHub Pages (one time, ~5 minutes)

1. Sign in to GitHub and go to https://github.com/new
2. Repository name: **`dilina-r.github.io`** (exactly this). Set it to **Public**. Click **Create repository**.
3. On the new repo page click **"uploading an existing file"**.
4. Drag in `index.html`, `cv.pdf` and `README.md` → click **Commit changes**.
5. Go to **Settings → Pages**. Under "Build and deployment", set Source = **Deploy from a branch**, Branch = **main**, folder **/ (root)** → **Save**.
6. Wait 1–2 minutes, then open **https://dilina-r.github.io** 🎉

### Using git instead (optional)
```bash
cd dilina-r.github.io
git init && git add . && git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/dilina-r/dilina-r.github.io.git
git push -u origin main
```

## Updating the site
Edit `index.html` on GitHub (click the file → pencil icon) or locally, then commit. The site updates within a minute or two.

- **Add a photo:** upload `photo.jpg`, then in `index.html` replace `<div class="avatar">DR</div>` with
  `<div class="avatar"><img src="photo.jpg" alt="Dilina Rajapakse"></div>`
- **Link a specific repo:** inside a project card's `plinks` div add
  `<a href="https://github.com/dilina-r/REPO-NAME" target="_blank" rel="noopener">Code</a>`
- **Add Google Scholar:** uncomment the Scholar line in the sidebar and put in your profile ID.
- **New paper:** copy one `<div class="pub">…</div>` block and edit it.

## Custom domain (optional)
Buy a domain (e.g. dilinarajapakse.com), then in **Settings → Pages → Custom domain** enter it and follow GitHub's DNS instructions. Tick **Enforce HTTPS**.
