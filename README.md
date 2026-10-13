# Shorts Studio public information pages

This folder contains only the public information website for the personal desktop application. It is designed for a dedicated GitHub Pages repository, `Aleksei-Kapa/shorts-studio-oauth-info`.

Expected public URLs after deployment:

- Homepage: https://aleksei-kapa.github.io/shorts-studio-oauth-info/
- Privacy: https://aleksei-kapa.github.io/shorts-studio-oauth-info/privacy.html
- Terms: https://aleksei-kapa.github.io/shorts-studio-oauth-info/terms.html

All styles and links are relative so the site works below the repository path. The site uses no JavaScript, external fonts, third-party embeds, analytics, or contact form. The contact email is an ordinary support address already used in the OAuth app branding.

## Public file allowlist

Only publish these files:

- `index.html`
- `privacy.html`
- `terms.html`
- `styles.css`
- `.nojekyll`
- `README.md` (optional)

Do not publish the parent project, app source, model files, runtime folders, credentials, tokens, user history, generated media, logs, or screenshots. Do not initialize or push a Git repository from the parent project directory. Use a separate repository checkout for deployment.

The website itself does not imply that the OAuth app or brand has been verified, that its publishing status has been changed, or that any channel feature has been enabled.

## Disclosure sources

- Google API Services User Data Policy: https://developers.google.com/terms/api-services-user-data-policy
- GitHub Pages data collection: https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#data-collection
- GitHub Privacy Statement: https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement

The privacy text was checked against the local YouTube client’s `youtube.readonly` and `youtube.upload` permissions, channel identity checks, video metadata checks, uploads, thumbnail updates, local credential storage, and durable upload/history records. Review and update it if those practices change.
