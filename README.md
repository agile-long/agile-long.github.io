# AGiLe — Project Page

Source for <https://agile-long.github.io/>.

**AGiLe: Learning Robust Long-Horizon Manipulation via Affordance-Grounded Bidirectional Latent Planning** (CVPR 2026)
Zixuan Chen, Xiangrong Feng, Jieqi Shi†, Lin Shao, Jing Huo†, Yang Gao · Nanjing University & NUS

Title, authors, abstract, contributions, BibTeX, and all figures are already filled in from the LaTeX source.

## Still to fill (only the Paper button)

In `index.html`, replace `PASTE_PAPER_PDF_URL` with your camera-ready / CVF PDF link
(or `static/pdfs/agile.pdf` if you host it here).

Optional: add homepage `href`s for the other authors, and a `static/images/favicon.ico`.

## Figures (already generated from figs/*.pdf)

| File | From |
|------|------|
| `static/images/teaser.png` | figs/teaser.pdf |
| `static/images/method.png` | figs/overview.pdf |
| `static/images/sim_tasks.png` | figs/sim_tasks.pdf |
| `static/images/results.png` | figs/real_results.pdf |
| `static/images/affordance.png` | figs/affordance.pdf (spare, not used yet) |

To swap a figure, just overwrite the PNG with the same name.


## Real-world video

`static/videos/real_world_demo.mp4` — transcoded from your upload to web-friendly H.264 (was H.265/58 MB, now ~3.6 MB, with faststart for streaming). Poster frame: `static/images/demo_poster.jpg`. The original H.265 would not play in Chrome/Firefox, so the page uses this H.264 version.

## Deploy

```bash
git clone https://github.com/agile-long/agile-long.github.io.git
cd agile-long.github.io
# copy these files in (include the hidden .nojekyll)
git add .
git commit -m "AGiLe project page"
git push
```

Check <https://agile-long.github.io/> after ~1 minute. If blank, go to
**Settings → Pages**, Source = "Deploy from a branch", Branch = `main` / `(root)`.

Uses Bulma + Font Awesome + Academicons from CDN — no build step.
