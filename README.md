# Dekyll

Dekyll is a blog theme for Jekyll with its own "Lab Log" design: a serif and mono type pair, a numbered log of entries, and light and dark themes. All configurations are under `_config.yml` file.
By default, Dekyll does not compatible with Github Pages.
You need to build locally and push to Github repository if you want to use Dekyll with Github Pages. In the future Dekyll will re-architecture as gem-based theme.

See [railsmine.net](https://www.railsmine.net) for demo.

## How to Run Dekyll on local machine

1. Make sure [Jekyll] is installed
2. Clone this repository. `git clone git@github.com:kuntoaji/dekyll.git`
3. Change directory to dekyll.
4. Run `bundle install`.
5. Run `bundle exec jekyll serve`

## Features

* Support Jekyll 4
* No Javascript required
* CSS Compression
* Recent posts below each post (optional)
* Responsive
* Support pagination
* Sitemap with Last-Modified-At
* Google Analytic and Disqus
* Jekyll SEO tag
* Pagination on Category and Tag pages

## How to Build
Google Analytic and Disqus are only rendered in production environment, you must set `JEKYLL_ENV=production` when building Dekyll.

```
JEKYLL_ENV=production jekyll build
```

[Jekyll]: https://jekyllrb.com/
