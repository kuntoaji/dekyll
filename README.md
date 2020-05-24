# Dekyll

Dekyll is a clean and minimal blog theme for Jekyll based on Minima theme, the Jekyll's default theme. All configurations are under `_config.yml` file.
By default, Dekyll does not compatible with Github Pages.
You need to build locally and push to Github repository if you want to use Dekyll with Github Pages. In the future Dekyll will re-architecture as gem-based theme.

## Demo
* [KAK Labs](https://www.kaklabs.com)
* [Railsmine](https://www.railsmine.net)

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
* Related articles
* Responsive
* Support pagination
* Sitemap with Last-Modified-At
* Social media sharing buttons
* Google Analytic and Disqus
* Jekyll SEO tag
* Pagination on Category and Tag pages

## How to Build
Google Analytic and Disqus are only rendered in production environment, you must set `JEKYLL_ENV=production` when building Dekyll.

```
JEKYLL_ENV=production jekyll build
```

[Jekyll]: https://jekyllrb.com/
