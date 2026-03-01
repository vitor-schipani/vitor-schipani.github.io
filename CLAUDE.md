# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a GitHub Pages site powered by Jekyll. Commits to `main` automatically trigger GitHub Pages to rebuild and deploy the site.

## Configuration

- **Theme**: `jekyll-theme-midnight` (set in `_config.yml`)
- **Hosting**: GitHub Pages at `vitor-schipani.github.io`

## Local Development

To preview the site locally, Jekyll must be installed:

```bash
gem install bundler jekyll
jekyll serve
```

Then visit `http://localhost:4000`.

## Content Structure

Pages are Markdown files with Jekyll frontmatter:

```yaml
---
layout: page
title: "Page Title"
permalink: /page-url/
---
```

- `layout: page` — standard page layout from the theme
- `permalink` — controls the URL path

The `about.md` file is the only content page currently. The `README.md` is not rendered as a site page.
