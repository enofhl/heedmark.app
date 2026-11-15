# Heedmark GitHub Pages site

A static landing page and privacy policy for Heedmark.

## Files
- `index.html` — one-page product landing page
- `privacy.html` — privacy policy
- `assets/styles.css` — responsive styling
- `assets/heedmark-mark.svg` — logo artwork

## Publish with GitHub Pages
1. Create a GitHub repository (or use the repository you want to publish from).
2. Upload the contents of this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.
6. Wait for GitHub Pages to publish. Your policy will be at `/privacy.html`.

If the repository is a project site, the relative links in these pages work under the repository path too.

## Before publishing
- Replace `[YOUR PRIVACY CONTACT EMAIL]` in `privacy.html` with a monitored contact address.
- Confirm the privacy statements against the exact release build and all enabled SDKs / dependencies. In particular, verify whether any analytics, crash reporting, advertising, cloud sync, or third-party services are included before publicly representing that no such collection occurs.
- Update the effective date whenever the policy is materially revised.
