# Miho Tanaka — Academic Profile Site (Hugo + PaperMod + Cloudflare Pages)

- Free hosting (Cloudflare Pages)
- Bilingual (ja/en)
- Optional: Decap CMS for browser-based edits

## Quick start
```bash
# Requires Hugo Extended
hugo server -D
```
Then push to GitHub and connect the repo on Cloudflare Pages:
- Build command: `hugo`
- Output directory: `public`
- Env var: `HUGO_VERSION` = your local version (e.g., `0.128.0`)

Decap CMS: edit `static/admin/config.yml` → `repo: yourname/yourrepo`.
Access CMS at `/admin/` after deployment (configure auth later).
