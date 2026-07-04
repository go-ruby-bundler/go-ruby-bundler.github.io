<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-bundler/brand/main/social/go-ruby-bundler.png" alt="go-ruby-bundler/go-ruby-bundler.github.io" width="720"></p>

# go-ruby-bundler.github.io

The organization's institutional landing page, served at
<https://go-ruby-bundler.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-bundler/docs](https://github.com/go-ruby-bundler/docs), served at
<https://go-ruby-bundler.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
