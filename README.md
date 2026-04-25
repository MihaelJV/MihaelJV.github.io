# MihaelJV.github.io
# MJV portfolio — static site

This folder contains the standalone static portfolio designed to drop into
`MihaelJV.github.io` (a GitHub Pages user repo).

## Files

- `index.html` — the page
- `styles.css` — all styles, no build step

## Deploy to MihaelJV.github.io

GitHub Pages user repos serve files from the **repo root** of the `main`
branch. Two equivalent options:

**Option A — copy to repo root (recommended)**

```bash
cp docs/index.html  /path/to/MihaelJV.github.io/index.html
cp docs/styles.css  /path/to/MihaelJV.github.io/styles.css
git -C /path/to/MihaelJV.github.io add index.html styles.css
git -C /path/to/MihaelJV.github.io commit -m "Add MJV portfolio"
git -C /path/to/MihaelJV.github.io push
```

**Option B — serve from `/docs`**

In the `MihaelJV.github.io` repo, go to *Settings → Pages → Build and
deployment* and set **Source: Deploy from a branch**, **Branch: main / docs**.
Then copy the entire `docs/` folder over.

## Notes

- No frameworks, no JS dependencies. Loads Inter + JetBrains Mono from
  Google Fonts.
- Dark mode follows the OS preference automatically.
- All identifying details (full name, country, employer names, specific
  project/people names) have been omitted by design.
