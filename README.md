# hugo-mock-landing-page

Overview
- Automates deployment of a Hugo static site using GitHub Actions.
- Deploys to GitHub Pages when changes are pushed to main.
GitHub Actions Workflow
- Triggers on push to main.
- Installs Hugo and builds the site.
- Deploys the site using peaceiris/actions-gh-pages.
Key Configurations
- config.toml updated with the correct baseURL.
- gh-pages branch set as the GitHub Pages source.
Workflow File: .github/workflows/deploy.yml
- Automates build and deployment for continuous updates.
