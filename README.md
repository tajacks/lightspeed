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
- Syntax Highlighting (highlight.js)

## JavaScript Requirements
`highlight.js` can be converted to CDN delivery, instead of local, by changing lines 12 & 12 in `head.html` from:


```
<link rel="stylesheet" type="text/css" href="{{ site.baseurl }}/assets/css/atom-one-dark.min.css" />
<script src="{{ site.baseurl }}/assets/js/highlight.min.js"></script>
```


To a CDN provider.

## Acknowledgements

CSS styles adapted and modified from Jeremy Thomas' 'Web Design in 4 Minutes'. 

Theme spacing, colours, and content layout feedback provided by my wife ♥
