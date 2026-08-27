# The Loyalist homepage

GitHub Pages-ready homepage combining an image-led editorial storefront with immersive scrollytelling.

Stories, categories, dates, links, excerpts, and featured images load from The Loyalist's public SNO/WordPress REST API. Images are pulled from the SNO gallery and are not stored in this repository.

## Publish

1. Upload these files to the root of a GitHub repository.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose `main` and `/ (root)`, then save.
5. Use the resulting GitHub Pages URL as an external link or iframe source in SNO.

The SNO origin is configured with the `SITE` constant in `index.html`. The public API and cross-origin requests must remain enabled.
