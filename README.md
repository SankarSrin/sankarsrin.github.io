# SankarSrin.github.io

Personal portfolio site, built with Jekyll and hosted on GitHub Pages.

## Editing content

Almost everything lives in plain YAML files, so updating the site never means touching HTML:

| What | File |
|---|---|
| Name, headline, "open to work" badge, CV link, profile links | `_config.yml` |
| Jobs | `_data/experience.yml` |
| Project cards | `_data/projects.yml` |
| Skills | `_data/skills.yml` |
| Publications (set `selected: true` to feature one on the home page) | `_data/publications.yml` |
| Education | `_data/education.yml` |
| Reviewing and leadership | `_data/service.yml` |

To add a CV: put the PDF in `assets/` and set `cv_file` in `_config.yml`.

## Preview locally

```
gem install jekyll jekyll-sitemap
jekyll serve
```
