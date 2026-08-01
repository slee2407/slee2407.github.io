# suy-lee.github.io

Suy Lee's personal blog, built with [Jekyll](https://jekyllrb.com/) using the
[Clean Blog](https://startbootstrap.com/theme/clean-blog) theme and deployed
via GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Writing a post

Add a new file to `_posts/` named `YYYY-MM-DD-title.html` (or `.md`) with
front matter like:

```yaml
---
layout: post
title: "Post title"
subtitle: "Optional subtitle"
date: YYYY-MM-DD HH:MM:SS +0900
background: '/img/bg-post.jpg'
---
```

## Analytics

Page views and referrers are tracked with [GoatCounter](https://www.goatcounter.com/).
Set `goatcounter_code` in `_config.yml` to your site code to enable it.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the
site with Jekyll and publishes it to GitHub Pages.

---

Theme based on [Start Bootstrap - Clean Blog Jekyll](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll),
MIT licensed.
