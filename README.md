# Ioannis Vlachos — academic website

Source for [yannisvl.github.io](https://yannisvl.github.io/), an academic website for presenting research, publications and background.

The site uses **Jekyll** and the **Academic Pages** template. The original template and theme authors retain their attribution; this repository contains the personal site's content and configuration.

## Find the content

| Location | Content |
| --- | --- |
| `_config.yml` | Site configuration and profile settings |
| `_pages/` | Main pages |
| `_publications/` | Publication entries |
| `_talks/`, `_teaching/` | Talks and teaching entries |
| `_portfolio/` | Project entries |
| `_data/` | Structured site data and navigation |
| `images/`, `files/` | Images and downloadable material |
| `_layouts/`, `_includes/`, `_sass/` | Template and presentation code |

## Preview locally

Install Ruby and Bundler, then run from this directory:

```bash
bundle install
bundle exec jekyll serve
```

Open **http://127.0.0.1:4000/**. The Gemfile determines the site dependencies; Ruby compatibility may need attention because the template spans older and newer tooling. A Dockerfile is also included.

## Editing workflow

Update the relevant Markdown content or configuration, preview the affected pages, and check navigation and downloadable-file links before publishing. JavaScript changes have a separate npm build described by `package.json`; routine content edits do not require rebuilding JavaScript.

See [contribution guidance](CONTRIBUTING.md) and [license](LICENSE). Upstream template: [Academic Pages](https://github.com/academicpages/academicpages.github.io).
