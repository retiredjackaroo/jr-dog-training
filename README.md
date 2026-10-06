# JR Dog Training website

A lightweight static website for JR Dog Training, serving Morisset and surrounding areas from Bonnells Bay, NSW.

## Local preview

Run a simple static server from the repository root:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publishing

The site is intended to publish from the root of the `main` branch with GitHub Pages. The `.nojekyll` file tells GitHub Pages to serve the static files directly.

## Updating photos

Replace the files in `assets/images/` while keeping the filenames unchanged, or update the corresponding image paths and dimensions in `index.html`.
