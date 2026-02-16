# Black Rose Site (Static v2)

Static website files for the **Black Rose** toolkit (Anno 117).

## Run locally
```bash
# from the project folder
python -m http.server 8080
# then open:
# http://localhost:8080
```

## Deploy on GitHub Pages (project repo)
1. Create a new GitHub repo (example: `black-rose-site`).
2. Upload **these files** to the repo root (same level as `index.html`).
3. In GitHub: **Settings → Pages**
   - **Build and deployment** → Source: **Deploy from a branch**
   - Branch: **main** (or `master`) / Folder: **/** (root)
4. Wait until Pages shows the site URL, then open it.

> Note: All links/assets are **relative**, so it works on `https://username.github.io/repo-name/` without changes.
