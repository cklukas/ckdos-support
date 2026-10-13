# CK-DOS Support Site

This repository hosts the support and privacy website for **CK-DOS** through
GitHub Pages. It follows the local sister project and public repository
[shoreform-support](https://github.com/cklukas/shoreform-support).

- Support: https://cklukas.github.io/ckdos-support/
- Privacy: https://cklukas.github.io/ckdos-support/privacy.html

## Publish

Push the site files to `main`. GitHub Pages uses **GitHub Actions** as its
source. `.github/workflows/pages.yml` builds the Markdown with Jekyll/minima
and deploys it automatically. The site needs no app credentials, API keys or
customer-data backend.

Keep support and privacy statements aligned with the shipped CK-DOS app.
Do not copy Shoreform's network-only-for-StoreKit statement: CK-DOS also offers
optional guest networking and a web compatibility proxy.

Local app implementation evidence is recorded in the CK-DOS repository's
`docs/app-store/LISTING-INPUTS.md`. This site is customer documentation, not
release qualification or a guarantee for every DOS program or adapter.
