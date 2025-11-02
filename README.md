# alanv.dev

My personal website.

## Overview
This repository contains a small static website with Portuguese and English versions.

- Primary pages: [index.html](/index.html) and [en/index.html](/en/index.html)
- Global styles: [style.css](/style.css)
- Web app metadata: [manifest.json](/manifest.json)
- Robots and sitemap: [robots.txt](/robots.txt), [sitemap.xml](/sitemap.xml)
- Cloudflare headers: [_headers](/_headers)
- Favicons and images: [img/](/img/)
- Editor settings ignored: [.gitigonre](/.gitigonre)

## Local preview
Serve the folder with a simple static server and open http://localhost:8000:

```sh
# Python 3
python -m http.server 8000

# or with Node.js
npx serve -l 8080 .
```

Then open:
- http://localhost:8000/ (Português)
- http://localhost:8000/en/ (English)

## Notes
- _headers is formatted for Cloudflare.  
- manifest.json points to dark-mode icons; the CSS switches images based on prefers-color-scheme.
- This repo is intentionally minimal.
