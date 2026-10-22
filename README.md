# Damot Auto Corporation — Website

One-page responsive website for Damot Auto Corporation, a complete auto repair & body shop at 1861 O'Connor Drive, Unit 4, North York, ON.

Designed & developed by [Melaku Digital Inc.](https://melakudigitalinc.com/)

## Structure

```
index.html                 The whole site (HTML, CSS and JS in one file)
assets/img/                Hero and before/after photos
assets/logo/               Current logo (piston badge), light version and icon/favicon
assets/logo/alternatives/  Gear and wheel logo options + presentation sheet
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000. Use your browser's device toolbar (Chrome DevTools → Toggle device toolbar) to check phone and tablet sizes.

## Before launch

- [ ] Replace sample used-car listings (`$xx,xxx`) with real inventory, prices and photos
- [ ] Replace social links (search `TODO: replace with Damot's real profile URLs`, two places)
- [ ] Connect the estimate form to a backend or form service (it currently formats the request for the customer to copy)
- [ ] Confirm hours, warranty, OMVIC registration, safety certificate and history-report claims with the owner
- [ ] Replace card-derived images with real shop photos

## Deploy

Static site, no build step. Works on GitHub Pages, Netlify, Vercel or Cloudflare Pages.
