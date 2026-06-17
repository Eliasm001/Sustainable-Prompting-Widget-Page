# Fit-to-Token GitHub Pages site

This folder contains a simple static website for the Fit-to-Token Chrome extension:

- `index.html` — application homepage
- `privacy.html` — privacy policy
- `terms.html` — terms of service
- `assets/logo.png` — app logo
- `styles.css` — shared styling

## Deploy on GitHub Pages

1. Create a public GitHub repository, for example `fit-to-token`.
2. Upload all files from this folder to the root of the repository.
3. Go to the repository’s **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`, then save.
6. After the site is published, use these URLs in the Google OAuth consent screen:
   - Homepage: `https://YOUR_GITHUB_USERNAME.github.io/fit-to-token/`
   - Privacy Policy: `https://YOUR_GITHUB_USERNAME.github.io/fit-to-token/privacy.html`
   - Terms of Service: `https://YOUR_GITHUB_USERNAME.github.io/fit-to-token/terms.html`

If the repository name is `YOUR_GITHUB_USERNAME.github.io`, the homepage URL will be `https://YOUR_GITHUB_USERNAME.github.io/` instead.
