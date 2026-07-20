# Personal site — Liesl Broadbridge

Built on the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (classic v0.16.3), hosted free on GitHub Pages.

## Editing content

- **About/home page**: `_pages/about.md`
- **CV**: `_data/cv.yml` (structured entries) and `assets/pdf/cv.pdf` (downloadable file)
- **Publications**: `_bibliography/papers.bib` (add a new `@article{...}` entry and it appears automatically)
- **News**: add a new file in `_news/` following the existing examples
- **Profile photo**: `assets/img/prof_pic.jpg`
- **Site settings / social links**: `_config.yml` and `_data/socials.yml`

## Deploying

Pushing to `main` automatically builds and deploys the site via the GitHub Actions workflow in `.github/workflows/deploy.yml` — no manual build step needed.
