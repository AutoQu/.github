# AutoQu

Modern landing page for AutoQu, automatically deployed to GitHub Pages.

## Features

- 🎨 Modern, responsive design with dark theme
- ⚡ Lightning-fast static HTML/CSS (no build step required)
- 🚀 Automatic deployment to GitHub Pages via GitHub Actions
- 📱 Mobile-friendly responsive layout

## Deployment

The landing page is automatically deployed to GitHub Pages when changes are pushed to the `main` branch. The deployment workflow is defined in `.github/workflows/deploy.yml`.

## Local Development

To run locally, simply open `index.html` in a browser, or use a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000
