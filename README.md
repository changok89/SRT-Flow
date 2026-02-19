# SRT-Flow

## Support Page (GitHub Pages)

`support/index.html` is configured to be deployed to GitHub Pages via Actions.

- Workflow file: `.github/workflows/deploy-support-pages.yml`
- Published URL (project pages): `https://<github-username>.github.io/SRT-Flow/`

### One-time setup

1. GitHub repo Settings -> Pages
2. Build and deployment -> Source: `GitHub Actions`
3. Push to `main` (or run workflow manually from Actions tab)

After deployment, `support/index.html` is served as the site root page.
