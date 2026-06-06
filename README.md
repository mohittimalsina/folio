# Mohit Timalsina — Honors Portfolio

Static site for publishing on **GitHub Pages** — no build step, no npm, no bundler.

## Files

```
index.html   ← main page (all JSX compiled in-browser via Babel)
styles.css   ← full stylesheet
images/      ← put your photos here, then update src= paths in index.html
README.md
```

## How to publish

1. Push this folder to a GitHub repository (or the `docs/` subfolder of one).
2. Go to **Settings → Pages → Source** and select the branch/folder.
3. GitHub will give you a URL like `https://yourusername.github.io/repo-name/`.

## Adding your photos

Replace the grey placeholder boxes with real images by adding `<img>` tags (or just the `src` attribute) wherever you see `portrait-placeholder` divs in `index.html`.  
Recommended: put images in an `images/` folder and reference them as `images/yourphoto.jpg`.

## Customizing

- **Theme / accent / font** — use the ⚙ settings button (bottom-right) live on the page.
- **Content** — edit the JSX sections directly inside the `<script type="text/babel">` block in `index.html`.
- **Styles** — edit `styles.css`.

No compilation needed — Babel runs in the browser automatically.
