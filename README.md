# LightSpeed

## About

LightSpeed A fast, simple, and privacy-respecting Jekyll theme. 
This theme acts as a landing page / personal website with post support. This theme was primarily created to act as a 
template for my personal website.

## Requirements

Add the following gems to your Gemfile:

```
gem "jekyll"
gem "jekyll-feed"
gem "jekyll-seo-tag"
gem "jekyll-paginate-v2"
```

Once added, run `bundle install` to install them if not present already. SEO is optional and can be removed without 
impacting other functionality.

## Features

- Post Support (Blog)
- Pagination and Dynamic Categories
- RSS Feed
- SEO
- Basic Mobile Support
- Syntax Highlighting (prism.js)

## JavaScript Requirements

### Syntax Highlighting

Syntax highlighting from `prism.js` can be customized and switched to a CDN provider if preferred by following 
[these](https://prismjs.com/index.html#basic-usage-cdn) instructions

### Analytics

Support for [Plausible Analytics](https://github.com/plausible) is provided by enabling it within `_config.yml`.

Example configuration: 

``` 
analytics:
  plausible:
    enabled: true
    site_fqdn: 'lightspeed.tajacks.com'
    script_source: 'https://plausible.io/js/script.js'
```

`enabled` - Boolean - To enable or disable page-view analytics.

`site_fqdn` - String - The FQDN of your website to report back to Plausible.

`script_source` - String - The source of the analytics script. Provided as a variable to accommodate self-hosted instances 
of plausible.

Support for more analytics platforms is a welcome suggestion, as long as they respect user privacy.

## Acknowledgements

CSS styles adapted and modified from Jeremy Thomas' 'Web Design in 4 Minutes'. 

Theme spacing, colours, and content layout feedback provided by my wife ♥
