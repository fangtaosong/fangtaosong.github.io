# Taosong Fang · 方陶松

Personal academic homepage built with [al-folio](https://github.com/alshedivat/al-folio) v1 and its pinned plugin gems.

## Local preview

Use Ruby 3.3, then run:

```bash
bundle install
bash run_server.sh
```

Open <http://127.0.0.1:4000/>. The development server rebuilds on changes and reloads the browser.

## Content

- `_pages/about.md`: biography and research interests
- `_pages/experience.md`: education and internships
- `_bibliography/papers.bib`: selected publications and publication links
- `_data/socials.yml`: email and profile links
- `_config.yml`: site settings

The GitHub Actions deployment workflow builds the site and publishes to the `gh-pages` branch. For deployment, configure GitHub Pages to serve from that branch.

Template source: `alshedivat/al-folio` at `ba1c8104a2f39c76ebc2fa9da1b02c66b75ea855`. Runtime layouts, styles, and scripts are supplied by the official theme gems; a local `_layouts/about.liquid` override keeps the English and Chinese names together in the homepage heading. Override tracking is recorded in `.al-folio-overrides.yml`. See `docs/` for upstream configuration guidance. The theme's MIT license is preserved in `LICENSE`.
