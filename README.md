# Keiter Family Gem Vault 💎

A sparkly, phone-friendly diamond auction price checker and private gemstone inventory.

## Deploy on Netlify from GitHub

1. On Netlify choose **Add new project → Import an existing project** and select GitHub.
2. Select **OliviaKeiter/gem-vault** and branch **main**.
3. Keep the build command empty and set the publish directory to `.` (configured by `netlify.toml`).
4. Deploy. Netlify gives you an HTTPS `netlify.app` address.
5. On your iPhone open the **Netlify address in Safari**. Tap **Share → Add to Home Screen** (or Safari's page menu) and enable **Open as Web App**.

## Your inventory privacy

The public site contains no personal jewelry records. Your inventory lives only in browser local storage. Import the starter inventory JSON file provided separately in your ChatGPT conversation under **My inventory → Import backup**. Do **not** upload that private JSON file to this public repo. Back up your collection regularly using **Back up vault** and save it to iCloud Drive.

Deleting the app or Safari site data, using a different browser, or moving to another domain may cause the locally stored inventory to become unavailable unless you have backed it up.

## Development

This is a static PWA. No build step or framework is needed. `index.html`, `sw.js`, `manifest.webmanifest`, and `icons/` are all served directly by Netlify.
