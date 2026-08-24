# Luke — Painting Studies

A two-page portfolio site:

- `index.html` — landing page with a scroll-triggered showcase of selected work
- `gallery.html` — full gallery of all paintings
- `paintings/` — full-resolution source photos, referenced by both pages via relative paths

## Editing

- Titles, medium, and descriptions live directly in the HTML — search for the painting title you want to change.
- The full list of gallery entries is in a `WORKS` array near the bottom of `gallery.html`.
- The showcase pieces on the landing page are the `.show-item` blocks in `index.html`.

## Hosting

This is a static site — no build step, no server. Once pushed to GitHub, it can be served for free with GitHub Pages (Settings → Pages → Deploy from branch → `main` → `/ (root)`).

Keep `paintings/` in the same folder as the HTML files — the image paths are relative.
