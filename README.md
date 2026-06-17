# Python Angola Website

A launch-ready static website for the Python Angola community initiative.

## Setup

### Add logo images

Create an `images/` folder and add your logos:
- `images/logo.png` — header logo (square format, ~50px minimum)
- `images/logo-circular.png` — hero section logo (circular format, ~400px minimum)

Recommended: PNG format with transparent background.

## What is included

- `index.html` — modern landing page with hero, roadmap, focus areas, and contact information.
- `styles.css` — polished dark theme design with smooth layout and logo integration.
- `script.js` — language detection and translation support for English, Português, and Français.
- `CNAME` — GitHub Pages custom domain configuration for `pythonangola.org`.

## How to use

1. Add your logo images to the `images/` folder (see Setup section above).
2. Open `index.html` locally to preview the website.
3. Update `contact@pythonangola.org` as needed.
4. Push the repository to GitHub.

## Deploying to GitHub Pages

1. Push the repository to GitHub.
2. In the repository settings, enable GitHub Pages for the `main` branch and root folder.
3. Add the custom domain `pythonangola.org` in GitHub Pages settings.
4. Ensure DNS points to GitHub Pages:
   - `A` records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - or use a `CNAME` record for `www` pointing to `username.github.io`.

## Notes

- The site loads in the visitor’s browser language and offers manual language switching.
- The site is ready to launch as a professional landing page and can be extended later with event pages, blog sections, or community resources.
