# Agent Guidelines — bact.github.io

Personal CV/academic site for Arthit Suriyawongkul, built on the al-folio v1.x Jekyll theme.

## What this repo owns

- Site config (`Gemfile`, `_config.yml`)
- Personal content: `_pages/`, `_posts/`, `_projects/`, `_news/`, `_teachings/`, `_bibliography/`
- Personal data: `_data/cv.yml`, `_data/socials.yml`, `_data/repositories.yml`, `_data/coauthors.yml`, `_data/citations.yml`
- Assets: `assets/img/`, `assets/pdf/`, `assets/json/`, `assets/rendercv/`
- CI/CD: `.github/workflows/deploy.yml`, `render-cv.yml`, `update-citations.yml`

Runtime (layouts, includes, Sass, plugins) lives in the `al_folio_core` and `al_*` gems — do not add those here.

## Validated local commands

```bash
bundle install
bundle exec jekyll serve          # dev server → http://localhost:4000/
bundle exec jekyll build          # production build to _site/
```

## Routing rules

- Personal content changes (bio, projects, publications, CV data): edit files in this repo.
- Theme/layout/feature bugs: report or PR to the upstream al-folio repos, not here.
- Do not add `_includes/`, `_layouts/`, `_sass/`, or `_scripts/` directories — those belong in gems.
