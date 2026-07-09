# Downpour — marketing site

Static landing page (single `index.html` + `assets/`). No build step.

**Deploy (any static host):** publish this folder as-is.
- GitHub Pages: push to a repo → Settings → Pages → deploy from branch (root).
- Cloudflare Pages / Netlify / Vercel: connect repo, output dir = `/` (root), no build command.

Custom domain: add a `CNAME` file (GitHub Pages) or set it in the host dashboard.
