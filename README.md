# humanworth.github.io

Personal site/blog for Ali Abbasi Tadi — AI security research, LLM evaluation, and career notes.

Built with Jekyll + the [minima](https://github.com/jekyll/minima) theme, hosted on GitHub Pages.

## Structure

- `index.md` — home page (introduction + highlights)
- `work-experience.md` — chronological work experience
- `_posts/` — blog posts (add new posts here as `YYYY-MM-DD-title.md`)

## Writing a new post

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md`:

```markdown
---
layout: post
title: "Your Title"
date: 2026-07-05
---

Your content here, in Markdown.
```

Push to `main` and GitHub Pages rebuilds the site automatically within a minute or two.

## Local preview (optional)

Requires Ruby + Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## To finish setup

- Fill in your LinkedIn and Google Scholar URLs in `_config.yml` (`minima.social_links`).
- In the repo's GitHub Settings → Pages, confirm the source is set to the `main` branch (should be automatic for a `<username>.github.io` repo).
