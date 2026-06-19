# CLAUDE.md

Guidance for Claude Code when working in this repo.

@AGENTS.md

## Context

This is a personal academic CV/portfolio site for Arthit Suriyawongkul (arthit@gmail.com), published at https://bact.github.io. It uses the al-folio v1.x Jekyll theme via Ruby gems — not a fork of the theme itself.

**Do not** add theme runtime files (`_layouts/`, `_includes/`, `_sass/`). All runtime is in gems.

## Dev loop

```bash
bundle install
bundle exec jekyll serve          # http://localhost:4000/
bundle exec jekyll build          # production build
```

## Key content files

| Path | Purpose |
|------|---------|
| `_pages/about.md` | Homepage / bio |
| `_pages/cv.md` | CV page (renders `_data/cv.yml` via rendercv) |
| `_data/cv.yml` | CV content in rendercv YAML format |
| `_bibliography/papers.bib` | Publications (BibTeX) |
| `_projects/` | Project cards |
| `_news/` | News/announcements |
| `_data/socials.yml` | Social media links |
| `_data/repositories.yml` | Pinned GitHub repos |
| `assets/img/prof_pic.png` | Profile photo |
