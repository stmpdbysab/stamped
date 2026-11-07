# Stamped

A small photo-first gallery for a stamp collection, published with GitHub Pages.

## Current gallery

The home page displays three scrolling rows. The uploaded test photo is `images.jpeg`, shown with its collection date, 6 November 2026. Selecting a photo opens a larger view.

## Add or remove photos

1. Upload each photo into the repository, beside `index.html` (or update its `src` path in `index.html`).
2. In `index.html`, add or remove an object in the `photos` array. Each entry has an image path, accessible alt text, a caption, and a title.
3. Commit the changes to `main`. GitHub Pages will publish the updated site from the configured source.

To remove the test photo, delete its entry from the `photos` array and remove `images.jpeg` from the repository. Keep at least one entry if you want the gallery to display a photo.
