# Sergey Bondarenko — one‑page site (Home + Speaking & Writing)

## Local preview
- **VS Code (Live Server):**
  1) Install the “Live Server” extension.
  2) Open the folder → right‑click `index.html` → “Open with Live Server”.
- **Python http.server:**
  ```bash
  # macOS/Linux/WSL
  python3 -m http.server 5500
  # Windows (if Python is installed)
  py -m http.server 5500
  ```
  Then open http://localhost:5500

## Edit
- Change texts and links in `index.html`.
- Replace `https://your-domain.com` in `index.html`, `robots.txt`, `sitemap.xml` with your real domain.
- Place images into `img/` and update the OG image path and avatar path.

## Deploy
- **GitHub Pages:** push to repo → Settings → Pages → GitHub Actions (default workflow).
- **Cloudflare Pages:** Create project → Direct Upload (upload the folder) or connect the repo.
