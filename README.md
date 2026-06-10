# Sourav Medya Academic Website

This branch is a local prototype migration of `souravmedya.github.io` from hand-written static HTML to the al-folio Jekyll academic website template.

## Local Build

Use Ruby 3.3.x and Bundler. With `mise`, the checked-in `.tool-versions` file selects Ruby 3.3.5:

```bash
mise install
bundle install
bundle exec jekyll serve
```

The production site should only be deployed after local review and approval.

## Content Locations

- `_pages/about.md`: homepage biography and profile metadata
- `_pages/publications.md`: research page
- `_bibliography/papers.bib`: structured publications
- `_pages/team.md`: students and alumni
- `_pages/teaching.md`: Teaching & Service page
- `_data/socials.yml`: contact and academic profile links
