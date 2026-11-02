# SideDish Legal

Public legal and account-deletion pages for SideDish, written in Markdown and
built with the same `jekyll-theme-minimal` theme as the other legal sites.

## GitHub Pages setup

1. Reuse the existing GitHub repository named `SideDish-legal` (this exact casing — the Pages URLs use it, e.g. `https://snickers-bar74.github.io/SideDish-legal/privacy/`). The local checkout is now `D:\Prosjekter\Legal\SideDish-legal`; its remote and repository root are unchanged.
2. In **Settings → Pages**, set **Source** to **GitHub Actions**.
3. Push to `main`. The Actions workflow builds the Jekyll site and deploys it.
   `_config.yml` excludes this README and the launch checklist.
4. Use these URLs in App Store Connect and Play Console:
   - `/privacy/`
   - `/terms/`
   - `/delete-account/`

Existing site base: `https://snickers-bar74.github.io/SideDish-legal/`.
Confirm its deployed state before store submission. See
[launch checklist](LAUNCH-CHECKLIST.md) for remaining release checks.
