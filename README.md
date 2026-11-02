# Silent Growth

Official site for the Silent Growth movement — quiet strength, the 30-day workbook, writing, and apparel.

**Live writing:** [sgrowth.substack.com](https://sgrowth.substack.com)

## What’s in this repo

| Path | Purpose |
|------|---------|
| `index.html` | Full site |
| `assets/architecture-of-silence.pdf` | Free 30-day workbook (English) |
| `assets/architecture-of-silence-zulu.pdf` | Free 30-day workbook (isiZulu) |
| `assets/tee-forest.jpg` | Forest green tee product shot |
| `assets/workbook-cover.jpg` | Workbook / Substack cover art |

## Publish free on GitHub Pages

1. Create a new **public** GitHub repository (e.g. `silent-growth` or `username.github.io`).
2. Upload everything in this folder to the **root** of the repo (or the `docs/` folder).
3. On GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`), folder: **/ (root)** — or `/docs` if you put files there
4. Save. In one or two minutes your site is live at:

   `https://YOUR-USERNAME.github.io/REPO-NAME/`

   If the repo is named `YOUR-USERNAME.github.io`, it will be:

   `https://YOUR-USERNAME.github.io/`

5. Optional: add a custom domain under **Pages → Custom domain** (the domain name itself usually costs money; hosting stays free).

### Quick upload without git (GitHub website)

1. Create the empty repo on github.com  
2. **Add file → Upload files**  
3. Drag in `index.html`, `README.md`, and the whole `assets/` folder  
4. Commit, then enable Pages as above  

### With git (optional)

```bash
cd silent-growth-site
git init
git add .
git commit -m "Silent Growth site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```

Then enable Pages on the `main` branch.

## Substack & apparel

- **Substack button** on the site points to `https://sgrowth.substack.com`
- **Apparel** section shows the forest green tee exactly as designed; order windows can be announced on Substack when ready

## Licence

Content © Silent Growth / Musawenkosi Vundla. Site structure free to host on GitHub Pages.
