# ujwaltikhe.github.io

Personal academic portfolio of **Ujwal Tikhe** — cybercrime investigator, digital forensics trainee and software developer. Built with Jekyll on the [academic-pages](https://github.com/academicpages/academicpages.github.io) template (Minimal Mistakes theme) and published to GitHub Pages.

Live site: <https://ujwaltikhe.github.io>

## Repository layout

| Path | Purpose |
| --- | --- |
| `_pages/` | Top-level pages: home (`about.md`), CV, publications, talks, dataset, blogs, misc, sitemap, 404 |
| `_portfolio/` | Project entries listed on `/portfolio/` |
| `_teaching/` | Teaching and training entries |
| `_publications/`, `_talks/`, `_posts/` | Reserved for future publications, talks and blog posts — archive pages show a "coming soon" notice while empty |
| `_data/` | Navigation and author metadata |
| `_includes/`, `_layouts/`, `_sass/`, `assets/` | Theme, layouts and styling |
| `images/` | Avatar and favicons |
| `.github/workflows/pages.yml` | Builds and deploys the site on every push to `main` |

## Local preview

```bash
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Or with Docker:

```bash
docker run --rm -v "%CD%:/srv/jekyll" -p 4000:4000 jekyll/jekyll:4 jekyll serve --config _config.yml,_config.dev.yml
```

## Adding content

- New project: add a markdown file to `_portfolio/` with `title`, `excerpt` and `collection: portfolio` front matter.
- New publication, talk or post: drop a markdown file into the matching collection folder; the archive pages pick it up automatically.

## License

Template and theme: MIT, (c) Michael Rose and academic-pages contributors — see [LICENSE](LICENSE). Site content: (c) Ujwal Tikhe.
