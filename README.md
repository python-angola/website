# Python Angola Website

A launch-ready static website for the Python Angola community initiative.

## What is included

- `index.html` — modern landing page with hero, roadmap, focus areas, and contact information.
- `styles.css` — polished dark theme design with smooth layout and hover interactions.
- `script.js` — language detection and translation support for English, Português, and Français.
- `CNAME` — GitHub Pages custom domain configuration for `pythonangola.org`.

## How to use

1. Open `index.html` locally to preview the website.
2. Update the Google Forms link in `index.html`:
   - Replace `https://forms.gle/YOUR_FORM_ID` with your actual form.
3. Update `contact@pythonangola.org` after email is configured.
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
