# SideDish Legal

Public, dependency-free legal and account-deletion pages for SideDish.

## GitHub Pages setup

1. Create a GitHub repository named `sidedish-legal` and push this folder as its repository root.
2. In **Settings → Pages**, set **Source** to **GitHub Actions**.
3. Push to `main`. The Actions workflow deploys the site.
4. Use these URLs in App Store Connect and Play Console:
   - `/privacy/`
   - `/terms/`
   - `/delete-account/`

The exact public origin will be shown by the GitHub Pages deployment, typically `https://YOUR-USERNAME.github.io/sidedish-legal/`.
