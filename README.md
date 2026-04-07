# ZeroToAsset Website

Static website for [zerotoasset.com](https://www.zerotoasset.com).

## Structure

```
build/                      ← deployable static files
├── index.html             ← homepage
├── about.html             ← about page
├── courses.html           ← course catalog
├── professionals-path.html ← C1 landing page
├── fba-operators-framework.html ← C2B landing page
└── logo.png

pages/                      ← work-in-progress pages
```

## Deployment

This repo deploys automatically to Netlify/Vercel/GitHub Pages on push to `main`.

**To deploy manually:** Drag the `build/` folder into Netlify drop zone.

## Editing

All pages are static HTML with inline CSS — no build step required.
Edit any `.html` file and push to deploy.

## Brand

- Navy: `#1A2332`
- Teal: `#3CC8B4`
- Gold: `#F5A623`
- Heading font: Crimson Pro (Google Fonts)
- Body font: System sans-serif stack
