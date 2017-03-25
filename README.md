
# Fueled Frontend Checklist for Websites

Originally forked from [drublic/checklist](https://github.com/drublic/checklist).

This should be included as `CHECKLIST.md` into every frontend project and each item should be ticked off or explained **before** launch:

```
- [X] This is done
- [ ] This is not done and must be done before launch
- [X] **[NIS]** This is not in scope and has been marked as done
```

### General
- [ ] Google Analytics Tracking Code is being used
- [ ] HTTP/2 is being used
- [ ] CDN is used for static files
- [ ] CDN is used for content pages
- [ ] Cookie-Less Domain is used for static files
- [ ] Add static asset revisioning (CSS & JS)
- [ ] DNS prefetching is used
  - [ ] `<link rel="preload" as="script">` (CSS, JS and fonts)
  - [ ] `<link rel="dns-prefetch">` (for Domain, which provides static resources, eg.: Images, and Tracking Tools)

### Resources

- [ ] JavaScript combined in one file
- [ ] JavaScript minified
- [ ] JavaScript is compressed
- [ ] No JavaScript inline
- [ ] CSS combined in one file
- [ ] CSS minified
- [ ] CSS is compressed
- [ ] CSS: No usage of @import
- [ ] No CSS inline
- [ ] HTML minified
- [ ] Static files are compressed with gzip or brotli
- [ ] Static files are pre-compressed on the server
- [ ] HTML is compressed with gzip or brotli
- [ ] Usage of correct image formats
- [ ] Usage of responsive images
- [ ] Images are optimized (ImageOptim…)
- [ ] Image are cached in the browser
- [ ] SVG files are minized
- [ ] SVG files are used where possible
- [ ] Only fonts that are used are loaded
- [ ] Browser cache is used efficiently
- [ ] ETags is not used
- [ ] Expires, cache-control and max-age headers for static resources is set to 1 year

- [ ] Asychronous or deferred loading of non-critical content
- [ ] Tracking scripts loaded asynchronously

### Measurements

Usually I measure the main pages of a project here.

- [ ] Count of all files
- [ ] Size of all files combined
- [ ] Download time of the page
- [ ] Google Page Speed analysis (Desktop, Mobile and Mobile UX; x of 100)
- [ ] SpeedIndex

### Rendering Performance

- [ ] Intrinsic image sizes are specified in the markup
- [ ] CSS is loaded in the document head
- [ ] Scripts are loaded at the end of the document
- [ ] Scripts are loaded with `defer`-attribute
- [ ] Scripts are loaded in the document head after styles are loaded
- [ ] Scrolling is possible with 60fps
- [ ] No usage of `document.write`
- [ ] CSS animation causing layout(reflow) is not heavily used

## Device performance

- [ ] CPU usage
- [ ] Memory usage
- [ ] GPU usage

## Cross-Browser

- [ ] Website is loading on all current desktop browsers (Safari, Firefox, Chrome, IE11, EDGE)
- [ ] Website is loading on all current mobile browser (Chrome for Android, iOS Safari)
- [ ] For Shops: Checkout is usable on all necessary devices and browsers
- [ ] Viewport Meta Tag is used correctly
- [ ] Usage of correct input types

# SEO

- [ ] Pages can be indexed
- [ ] Mobile version of website is available
- [ ] HTTPS is used on all pages
- [ ] Sitemap is available
- [ ] Structured-Data is used where possible
- [ ] Headlines used
- [ ] Headlines in correct order
- [ ] Meta descriptions used
- [ ] Meta keywords used
- [ ] Meta title is filled correctly

- [ ] Keywords used in headlines
- [ ] Images use the `alt`-attribute
- [ ] Links use a `title`-attribute
- [ ] Links in navigation do not use `title`-attribute
- [ ] No Duplicate Content
- [ ] Usage of absolute URLs

- [ ] Internal links point to HTTPS version of page
- [ ] Redirects are done with 301
- [ ] No 404-errors
- [ ] No 500-errors
- [ ] Canonical Tags are used if applicable

## Accessibility

- [ ] Color Contrast is good (WCAG 2.0)
- [ ] WAI-ARIA roles are used
- [ ] Usage of accessible elements like nav, footer, aside
- [ ] URLs are accessible
- [ ] Keyboard accessibility is available
- [ ] Correct input types are used

## Security

- [ ] HTTPS is used on all pages
- [ ] There is no mixed content on the pages
- [ ] external plugins and trackings get loaded via HTTPS
- [ ] Robots.txt is in use
- [ ] Cross-Site-Scripting is not possible
- [ ] HSTS Header is set
- [ ] Content-Security-Policy is set and only allows specific hosts and no inline scripts

## More

- [ ] Strict usage of domain with or without www
- [ ] Correct language set in HTML tag
- [ ] Charset is set
- [ ] HTML is valid
- [ ] 404-page is available
- [ ] A special print style sheet is in place

### Server

- [ ] Correct language set by the server
- [ ] Correct content types set by the server
