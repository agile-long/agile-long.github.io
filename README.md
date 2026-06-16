# AGiLe — Project Page

Source for <https://agile-long.github.io/>.

## What to edit (all in `index.html`, marked with `EDIT` / `REPLACE` / `PASTE_` comments)

1. **Authors** — fill the full author list and affiliations (currently has placeholders).
2. **Link buttons** — replace `PASTE_PAPER_PDF_URL`, `PASTE_ARXIV_ID`, `PASTE_CODE_REPO`, `PASTE_VIDEO_URL`. Delete any button you don't have yet.
3. **Teaser** — drop `static/images/teaser.png` (or switch to the `<video>` block) and rewrite the caption.
4. **Abstract** — replace the placeholder paragraph with the final camera-ready text.
5. **Method / Results** — add `static/images/method.png`, `static/images/results.png` and captions.
6. **BibTeX** — fill `PASTE_OTHER_AUTHORS`.
7. **Meta** — title, description, and `static/images/og_banner.png` (1200×630) for link previews.

## Media files to add

| File | Purpose |
|------|---------|
| `static/images/teaser.png` | top banner |
| `static/images/method.png` | architecture figure |
| `static/images/results.png` | results |
| `static/images/og_banner.png` | social preview (1200×630) |
| `static/images/favicon.ico` | site icon |
| `static/videos/teaser.mp4` | optional teaser video (<10 MB) |
| `static/pdfs/agile.pdf` | paper PDF (optional) |

## Deploy

```bash
git clone https://github.com/agile-long/agile-long.github.io.git
cd agile-long.github.io
# copy these files in, edit index.html, add media
git add .
git commit -m "AGiLe project page"
git push
```

Then check <https://agile-long.github.io/> after ~1 minute. If it doesn't appear,
go to **Settings → Pages**, set Source to "Deploy from a branch", Branch = `main` / `(root)`.

The page uses Bulma, Font Awesome, and Academicons from CDN — no build step needed.
