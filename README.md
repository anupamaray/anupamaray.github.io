# anupamaray.github.io

Personal website of **Anupama Ray** — Senior Research Scientist, IBM Research.

🔗 **Live site:** https://anupamaray.github.io

## About

A single-page academic and professional profile covering research, publications,
patents, talks, teaching, awards, and professional service. Built as plain,
self-contained HTML (no build step, no framework) and served free via GitHub Pages.

## Structure

| File | Purpose |
|------|---------|
| `index.html` | The entire site — markup and CSS inline, with a light/dark theme toggle |
| `profile.jpg` | Profile photo |
| `files/AnupamaRay_CV.pdf` | Downloadable CV (linked from the header) |
| `robots.txt`, `sitemap.xml` | Search-engine discoverability |

The page includes JSON-LD structured data and Open Graph tags in `<head>` so search
engines and LLMs can identify the profile and its linked accounts (LinkedIn, Google
Scholar, DBLP, GitHub).

## Updating the site

1. Edit `index.html` (or swap in a new `profile.jpg` / `files/AnupamaRay_CV.pdf`).
2. Commit and push to the `master` branch:
   ```bash
   git add -A
   git commit -m "Update site"
   git push origin master
   ```
3. GitHub Pages rebuilds automatically; changes are live in ~1–5 minutes.

No local server or build is required — opening `index.html` in a browser previews it exactly.

## Links

- [Google Scholar](https://scholar.google.com/citations?user=FUjYQ-8AAAAJ&hl=en)
- [DBLP](https://dblp.org/pid/136/3987.html)
- [LinkedIn](https://www.linkedin.com/in/anupama-ray-55140826/)
