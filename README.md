# Cerulean Residences

A small Jekyll blog designed for GitHub Pages.

## Publish it

1. Push the `main` branch to GitHub.
2. In the repository, open **Settings → Pages** and choose **GitHub Actions** as the publishing source.
3. The included workflow builds and deploys the site after every push to `main` (or can be run manually from the Actions tab).

Because this is a user-site repository, its published address will be `https://ceruleanresidences.github.io/` when the repository belongs to the `ceruleanresidences` GitHub account or organization.

## Write a post

Create a Markdown file in `_posts` named `YYYY-MM-DD-title.md` with front matter like:

```yaml
---
title: A thoughtful title
date: 2026-10-04 09:00:00 -0500
categories: [Journal]
---
```

The post will appear on the home page and archive automatically. Use `<!--more-->` where you want the home-page excerpt to end.

## Preview locally

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`.
