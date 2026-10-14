# StayBroker

Premium, image-first static website for [staybroker.in](https://staybroker.in/), built for GitHub Pages. The site has no backend or build step.

## Publish

1. Publish the repository root with GitHub Pages.
2. Keep the root `CNAME` file set to `staybroker.in` and point the domain's DNS records to GitHub Pages.
3. Keep `robots.txt`, `sitemap.xml`, and `.nojekyll` at the site root.

## Site assets

- The original StayBroker logo is used from `assets/logo.svg`; replace it only with the approved source logo file.
- Homepage photography is bundled as WebP in `assets/images/`. The sample portfolio photos and labels are illustrative placeholders; replace them with approved project names, locations, and images before presenting them as real listings.
- Contact details, page metadata, and structured data are in `index.html`.

The photography is sourced from Unsplash and served locally so the homepage does not rely on a third-party image request at runtime.
