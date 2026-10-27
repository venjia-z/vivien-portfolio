# Vivien Zhang — Portfolio

Personal portfolio of Vivien Zhang, product and campaign marketing at GMI Cloud.

The site is a single self-contained `index.html`: no build step, no dependencies to install. All images are embedded, and the only outside requests are Google Fonts and links out to X, LinkedIn and gmicloud.ai.

## What's inside

- **Opening:** a pixel eye that opens onto the landing page (plays on the home page only; click or press any key to skip).
- **Home:** the pixel eye and ocean scene with headline numbers.
- **Work:** a desktop of draggable windows. Four albums (Product launch, Co-marketing campaign, Social and community, Branding) play their tracks like stories; press **Play** or use the dock to spin an album on the vinyl player, then open any track's case study.
- **About** and **Contact.**

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publish with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

To use your own domain, add it under **Settings → Pages → Custom domain**.

## Editing

Everything lives in `index.html`:

- **Styles** are in the `<style>` block in `<head>`.
- **Projects and metrics** are in the `<script>` block: the `C` array (projects), `PLAIN` (titles and one-liners) and the `Object.assign(C.find(...))` lines (case-study details and numbers).
- **Album names and colors** are in `RECS` and `LBL`.

## Credits

Design and content: Vivien Zhang. Built with help from Claude.
