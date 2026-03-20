# BrandLedger Support Site

This folder is ready to publish with GitHub Pages.

## Files

- `index.html` - Support URL page for App Store Connect
- `privacy.html` - Privacy Policy URL page for App Store Connect
- `styles.css` - Shared styling

## Before publishing

1. Replace `support@brandledger.app` in `index.html` and `privacy.html` with your real support email.
2. If needed, update the company name, address, or response-time wording.
3. Push these files to a GitHub repository.

## GitHub Pages options

### Option 1: Repository root with docs folder

- Push this project to GitHub
- Open repository `Settings > Pages`
- Set source to `Deploy from a branch`
- Choose your main branch and `/docs`

Result:

- Support URL: `https://YOUR_GITHUB_USERNAME.github.io/REPOSITORY_NAME/`
- Privacy URL: `https://YOUR_GITHUB_USERNAME.github.io/REPOSITORY_NAME/privacy.html`

### Option 2: Dedicated support repository

- Create a repository such as `brandledger-support`
- Upload these files into the repository root or `docs`
- Enable GitHub Pages

Possible result:

- Support URL: `https://YOUR_GITHUB_USERNAME.github.io/brandledger-support/`
- Privacy URL: `https://YOUR_GITHUB_USERNAME.github.io/brandledger-support/privacy.html`
