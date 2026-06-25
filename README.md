# The Sobo — Indian Street Food (website)

A single-file, fully responsive website for **The Sobo** (Waterloo, ON).
Everything — design, animations, menu, photos, SEO/JSON-LD — is contained in
`index.html`. No build step, no dependencies.

## Put it live on GitHub Pages

1. Create a new **public** repository (name it whatever you want the URL to be,
   e.g. `sobo`).
2. Click **Add file → Upload files**, drag in `index.html`, `.nojekyll` and
   this `README.md`, then **Commit changes**.
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Branch: **main**, folder: **/ (root)**, then **Save**.
6. Wait ~1 minute. Your site is live at:
   **https://arjuncad02.github.io/sobo/**
   (replace `sobo` with whatever you named the repo).

## Editing

Open `index.html` and edit the single `CONFIG` block near the top — name,
colours, menu, prices, contact and order links. Food photos live in the
`IMAGES` block and are referenced by key (e.g. `img:"pav_bhaji"`).

`.nojekyll` tells GitHub Pages to serve the files as-is. Keep it in the repo.
