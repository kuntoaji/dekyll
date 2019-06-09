# Dekyll

Jekyll theme based on default Jekyll's default style. All configurations are under `_config.yml` file.
By default, Dekyll does not compatible with Github Pages.
You need to build locally and push to Github repository if you want to use Dekyll with Github Pages. In the future Dekyll will re-architecture as gem-based theme.

### Demo
* [KAK Labs](https://www.kaklabs.com)
* [Railsmine](https://www.railsmine.net)

### Dependencies
* jekyll 3.8.5
* jekyll-sitemap 1.2.0
* jekyll-seo-tag 2.5.0
* jekyll-paginate-v2 2.0.0
* jekyll-last-modified-at 1.0.1

### Features
* Support Jekyll 3
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

### How to Build
Google Analytic and Disqus are only rendered in production environment, you must set `JEKYLL_ENV=production` when building Dekyll.

```
JEKYLL_ENV=production jekyll build
```
