# Auger & Spade Website

This folder contains a complete static website that can be hosted free with GitHub Pages.

## Files

- `index.html` — website content
- `styles.css` — colors, layout, and mobile styling
- `script.js` — mobile menu and automatic copyright year
- `assets/ryan-hodges-headshot.jpg` — headshot used in the About the Principal section
- `CNAME` — custom domain placeholder

## Publish with GitHub Pages

1. Sign in to GitHub and create a new repository. A name such as `auger-and-spade` is fine.
2. Upload every file and folder from this package to the repository.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then save.
6. GitHub will provide a temporary web address after the site publishes.

## Connect your .com domain

1. The `CNAME` file is already configured for `augerandspade.com`.
2. In GitHub Pages settings, enter `augerandspade.com` under **Custom domain**.
3. At your domain registrar, update the DNS records using GitHub's instructions.
4. After DNS finishes updating, enable **Enforce HTTPS** in GitHub Pages.

## Edit the site later

The easiest edits are made directly in `index.html`. Search for the visible wording you want to change, replace it, and commit the change. Most appearance changes are in `styles.css`.
