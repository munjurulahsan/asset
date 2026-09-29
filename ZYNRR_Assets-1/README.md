# ZYNRR™ Cloud Assets Guide

This directory contains all visual and media assets for the **ZYNRR™** web application.

## Directory Structure

```
ZYNRR_Assets/
├── brand/
│   └── zynrr-logo.svg
├── campaign/
│   ├── brand-close.webp
│   ├── campaign-main.webp
│   └── campaign-secondary.webp
├── hero/
│   ├── hero-alternate.webp
│   ├── hero-close.webp
│   ├── hero-main.mp4
│   └── hero-poster.webp
├── lifestyle/
│   ├── movement.webp
│   ├── urban-collage.webp
│   ├── urban.webp
│   └── weather.webp
├── material/
│   ├── fabric-macro.webp
│   ├── water-01.webp
│   ├── water-02.webp
│   └── water-03.webp
└── product/
    ├── collection/
    │   ├── collection-01-front.webp
    │   ├── collection-01.webp
    │   ├── collection-02.webp
    │   ├── collection-03.webp
    │   └── collection-04.webp
    ├── details/
    │   ├── jacket-hood.webp
    │   └── jacket-zipper-board.webp
    └── master/
        ├── jacket-3quarter.webp
        ├── jacket-back.webp
        └── jacket-front.webp
```

---

## Cloud Hosting & Integration Instructions

Once you upload these files to your Cloud / CDN provider (e.g. Cloudinary, AWS S3, Cloudflare R2, Supabase Storage, or Firebase Storage):

All project assets are mapped centrally in `ZYNRR/src/assets.js`.

You can simply define a base CDN URL prefix in `src/assets.js`:

```javascript
// Example:
const CDN_BASE_URL = 'https://your-cdn-or-bucket.domain.com/assets'
const assetUrl = (path) => `${CDN_BASE_URL}${path}`

// Then use:
// heroVideo = assetUrl('/hero/hero-main.mp4')
// jacketFront = assetUrl('/product/master/jacket-front.webp')
```
