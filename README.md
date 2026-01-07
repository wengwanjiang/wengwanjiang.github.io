This repository hosts the source for Wanjiang Weng's academic homepage.

## Structure

- `index.html`: Single-page homepage (entry point)
- `assets/`: Site-owned static assets
	- `assets/css/`: Custom styles
	- `assets/js/`: Small site scripts
	- `assets/img/`: Images (avatar, publication teasers, favicon)
	- `assets/files/`: PDFs and other downloadable files
- `vendor/`: Third-party libraries that may be used by the site

## Local preview

From the repo root:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## Notes

- If you want a CV link on the homepage, put your PDF into `assets/files/` and add the link in `index.html`.
