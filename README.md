# Hugo Mock Landing Page (Auto-deployed)

A mock product landing page built with Hugo and automatically deployed to GitHub Pages using GitHub Actions.

## Automated Deployment

This project uses GitHub Actions to automatically build and deploy the Hugo website whenever changes are pushed to the main branch.

The workflow (defined in `.github/workflows/gh-pages-deployment.yaml`):
- Checks out the repository with submodules
- Sets up Hugo environment (v0.144.1)
- Builds the static site with minification
- Publishes to the gh-pages branch

