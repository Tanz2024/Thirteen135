# Thirteen135

Static marketing site for Thirteen135, a Malaysia-based Microsoft 365 enquiries and support business.

## Run locally

Open `index.html` in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8080
```

## GitHub Pages

Push the repository to GitHub, then open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save. The site is intentionally buildless so GitHub Pages can serve it directly.

The contact form uses a `mailto:` fallback and does not store submissions.
