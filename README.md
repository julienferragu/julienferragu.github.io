# Julien Ferragu Website

Minimal personal site built on top of the `academicpages` Jekyll template and hosted on GitHub Pages.

The site is intentionally narrow:

- homepage as a short evidence dossier
- `CV` page
- `Portfolio` page with focused case studies

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open `http://localhost:4000`.

## Content structure

- `_pages/about.md`: homepage
- `_pages/cv.md`: CV page
- `_pages/portfolio.html`: portfolio index
- `_portfolio/`: case studies
- `_config.yml`: site identity and sidebar settings

## Notes

- The repository keeps the original Jekyll template structure but removes most of the default demo content.
- PDF assets can be dropped into `files/` later and linked from the CV or portfolio pages.
