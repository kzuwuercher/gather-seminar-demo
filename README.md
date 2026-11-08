# Gather seminar demo

Static GitHub Pages version of the editable Gather revibe.

## Runtime and data

Python runs in each visitor's browser through Pyodide v314.0.7, loaded from the official jsDelivr CDN. The first run downloads the runtime and Python packages (about 40 MB), so an internet connection is required. The sample data is built into the page. Execution history stays in that visitor's browser; there is no shared backend or central log.

## Publish

Set the repository's Pages source to **GitHub Actions** in **Settings → Pages**. Then push the site files to `main`; the included workflow deploys the site on each push.
