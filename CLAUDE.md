# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

Static Jekyll site (GitHub Pages) for the "Open Challenges in Robot Control – Part II" IFAC2026 workshop. No app code, no build scripts, no tests — content and styling only. Deployed automatically via GitHub Pages when pushed to `main`.

## Commands

No package.json / Gemfile is committed (`.gitignore` excludes `Gemfile`, `Gemfile.lock`, `.bundle/`, `vendor/`), so there's no in-repo build tooling. To preview locally, a Ruby+Jekyll toolchain must be set up ad hoc:

```
gem install bundler jekyll
bundle init && bundle add jekyll github-pages
bundle exec jekyll serve
```

There is no lint or test suite. Verify changes by checking that HTML/Liquid renders correctly and that content edits keep the page's structure intact.

## Architecture

- **`_config.yaml`** — site title/description and theme (`jekyll-theme-cayman`, pulled in as a remote gem, not vendored in-repo).
- **`index.md`** — the entire page content (single-page site). Front matter here (`title`, `display_title`, `description`, `date`, `venue`) feeds directly into `_layouts/default.html`. Content sections (Overview, Target Audience, Invited Speakers, Program Schedule, Organizers, Expected Outcomes) are plain Markdown/HTML mixed together — speaker/organizer entries use a repeated `.profile-card` HTML block, not a Jekyll collection/data file, so adding a person means copy-pasting a card block and adding a photo under `assets/speakers/` or `assets/organizers/`.
- **`_layouts/default.html`** — wraps `index.md` content. Renders the header (`page-header`) from front matter (`display_title`/`title`, `description`, `date`, `venue`), and injects the two header logos (`assets/logos/ifac_2026_logo.svg`, `assets/logos/robot_control_tc.svg`) via a `custom-header-logos` div that JS moves into `.page-header` on `DOMContentLoaded`. Footer is hardcoded here (IFAC 2026 / venue / copyright).
- **Styling**: `assets/css/style.scss` imports the Cayman theme and overrides `.page-header` background gradient and heading colors. `_sass/_workshop.scss` holds all custom component styles (event-meta badges, header logos, program table, `.profile-grid`/`.profile-card`/`.profile-image`/`.profile-info`) and is presumably `@import`-ed by the theme's own SCSS chain — check `_sass/jekyll-theme-cayman.scss` if styles don't seem to apply.
- Editing venue/date: update the `date`/`venue` front matter fields in `index.md`; `"To be announced"` is the current placeholder for venue.
