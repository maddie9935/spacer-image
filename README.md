# Spacer images example

Demo pages for the "spacer image missing alt text" accessibility error.

- `index.html` has the error. Four white spacer images (`spacer.gif`) have no `alt` attribute, so screen readers announce the filename.
- `fixed.html` has the fix. Each spacer image has `alt=""`, so screen readers skip it.
- `spacer.gif` is a blank white image. It's invisible on the white page.
- `styles.css` holds the shared styles.

To show where the spacer images are while recording, add `#show-spacers` to the end of either page's address (for example, `index.html#show-spacers`). This outlines each spacer with a dashed line. Remove it to hide them again.

To host it, push these files to a repo and turn on GitHub Pages (Settings > Pages > Deploy from branch > `main` / root).
