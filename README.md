# Safer Driver Training

Website for Safer Driver Training, a driving instructor based in Eccleshall, Staffordshire.

Static site — no build step. `index.html` and `contact.html` share `styles.css` (fonts inlined there); photos and the coverage map are inlined directly in the page markup. Deploys as-is to Cloudflare Pages with no build command and no output directory other than the repo root.

Contact form on `contact.html` submits via [Web3Forms](https://web3forms.com) (the access key in the form is a public client-side key, not a secret).

Currently a first-pass design concept, not the final site.
