# Vivien Zhang — Portfolio

Personal portfolio of Vivien Zhang, product marketing and campaigns at GMI Cloud.

The whole site is one self-contained `index.html`: no build step and no dependencies. Images are embedded; the only outside requests are Google Fonts and links out to X, LinkedIn and gmicloud.ai.

## What's inside

- **Opening:** a pixel eye that opens onto the landing page (home only; click or press any key to skip).
- **Home:** the pixel eye and ocean scene with headline numbers.
- **Work:** an editorial list of 14 case studies, filterable by section. Each cover is a stippled desktop with retro tab windows showing the key numbers.
- **Case studies:** a rotating billboard cover, results, what I led, and context.
- **About** and **Contact.**

## Run it locally

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Deploy

**GitHub Pages:** push to GitHub, then Settings → Pages → Deploy from a branch → `main` / `(root)`.

**Vercel:** import the repo at vercel.com/new, framework preset "Other", no build command, no output directory. Every push to `main` redeploys.

## Editing

Everything lives in `index.html`:

- Styles: the `<style>` block in `<head>`.
- Projects and copy: the `C` array, `PLAIN`, and the `Object.assign(C.find(...))` lines in the `<script>` block.
- Section names and colors: `TIERS`.

To add a resume later, put the PDF next to `index.html` and add a link to it in the top bar.
