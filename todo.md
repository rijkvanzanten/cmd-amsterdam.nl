# TODO

## Miscellaneous

*   Tip: Apart Profiel / gebruiker in Chrome zonder plugins

## HTTP optimisation

*   Use a [CDN](https://www.cloudflare.com)

### HTTP/1

*   Concatenate
*   Icon fonts
*   Domain Sharding

### HTTP/2

*   Don’t concatenate
*   No icon fonts
*   No Domain Sharding

## Audits

*   [PageSpeed](https://developers.google.com/speed/pagespeed/insights/)
*   [WebPageTest](https://www.webpagetest.org)
*   [Chrome Dev Tools](https://developer.chrome.com/devtools)
*   [Chrome Audits](https://developer.chrome.com/extensions/experimental_devtools_audits)

## Minify

### CSS

*   [clean-css](https://github.com/jakubpawlowicz/clean-css)
    — Fast and efficient CSS optimizer for node.js and the Web
*   Don't load unused CSS (like the WooCommerce CSS etc)

### HTML

*   [html-minifier](https://github.com/kangax/html-minifier)
    — Javascript-based HTML compressor/minifier

### JavaScript

*   [Uglify](https://github.com/mishoo/UglifyJS2)
    — JavaScript parser / mangler / compressor / beautifier toolkit
*   Load JS that isen't required for the page to render correctly asynchronously

### Fonts

### Images
