# kheesu.com

Source for my personal academic website, published at [kheesu.com](https://kheesu.com) via GitHub Pages.

Built on [academicpages](https://github.com/academicpages/academicpages.github.io), a Jekyll fork of
[Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/).

## Where things live

| What | Where |
|---|---|
| Homepage, research, talks index | `_pages/` |
| Publications | `_publications/` (one file per paper) |
| Talks and posters | `_talks/` (one file per talk) |
| CV content | `_data/cv.json` — rendered at `/cv/` by `_includes/cv-template.html` |
| CV PDF | `files/cv.pdf` |
| Nav bar | `_data/navigation.yml` |
| Site settings, author profile, social links | `_config.yml` |
| Styles | `_sass/` |

`_data/cv.json` is the single source of truth for the HTML CV. Keep it in sync with `files/cv.pdf`
by hand — there is no generator.

## Running locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>. `_config.yml` is not hot-reloaded; restart the server after
editing it.

Alternatively, with Docker:

```bash
docker compose up
```

## Adding content

A publication is a Markdown file in `_publications/` named `YYYY-MM-DD-slug.md`. Keep the filename
date, the `date:` field, and the `permalink:` consistent. `category:` must match a key under
`publication_category` in `_config.yml` (`conferences` or `under_review`).

A talk is a Markdown file in `_talks/` named `YYYY-MM-DD-slug.md`, with `type`, `venue`, `date`, and
`location`.

For math or diagrams on a page, opt in with `mathjax: true` or `mermaid: true` in the front matter —
the scripts are not loaded otherwise.
