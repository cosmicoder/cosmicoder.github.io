# Aniket Sanghi's Personal Website

Jekyll site on the Beautiful Jekyll 5.0 theme, served by GitHub Pages at https://cosmicoder.github.io.

## Pages

| URL | File | Navbar | Images (`assets/img/`) |
|---|---|---|---|
| `/` | `index.html` | Site title | Cover rotation: `aCenAb.jpg`, `Kepler186f.jpeg`, `lhs475b.jpeg`. Body: `intro_web.jpg`, `pr-image.jpg` |
| `/aboutme` | `aboutme.html` | About Me | Cover: `art-cahill.jpeg`. Body: `Exo6-Talk.jpg`, `website_teff_sma.jpg` |
| `/mentors` | `mentors.html` | Mentors | Cover: `lighthouse.jpeg`. Photos: `dimitri.jpg`, `CB.jpg`, `brendan.jpeg`, `Mike_Liu.jpg`, `yifan_2.jpeg`, `jason.jpg`, `jerry_2.jpeg`, `will.jpeg` |
| `/press` | `press.html` | Press | Cover: `aCenAb.jpg`. Outlet logos load from external URLs |
| `/assets/img/Sanghi_Aniket_CV.pdf` | — | CV | — |
| `/404.html` | `404.html` | — | — |

The navbar avatar is `DHG_Headshot.jpeg`.

## Configuration

`_config.yml` sets the site title, navbar links, avatar, footer social links, and colors. To add a page, create `<name>.html` with `layout: page` front matter and list it under `navbar-links`.

## Theme

These files come from Beautiful Jekyll and are kept intact. Pages use the `page` layout; `404.html` uses `default`.

- `_layouts/`, `_includes/`: templates. The analytics and comment includes render nothing until enabled in `_config.yml`.
- `assets/css/`, `assets/js/`: theme styles and scripts.
- `_data/ui-text.yml`: comment-form labels.
- `feed.xml`: RSS feed, linked from every page's `<head>`.
- `Gemfile`, `beautiful-jekyll-theme.gemspec`: local build dependencies.
- `.github/workflows/ci.yml`: builds the site on every push.
- `LICENSE`: the theme's MIT license.

## Archive

`_archive/` holds retired files at their original paths. Jekyll ignores folders that start with `_`, so none of it is published. To restore a file, `git mv` it back to its original path.

- Pages removed from the navbar (Academics, Activities, Research: `planets`, `bd`, `more`, `research`) and the images only they used.
- Images no page references.
- Theme demo content: sample posts, `tags.html`, `CHANGELOG.md`, `staticman.yml`, and the theme author's `.github` templates and funding file.
