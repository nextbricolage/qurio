# Qurio — public legal pages

Static pages for **Qurio Q&A for Confluence** (published by **nxb labs**),
served via GitHub Pages at:

- Home: https://nextbricolage.github.io/qurio/
- Privacy Policy: https://nextbricolage.github.io/qurio/privacy.html
- Impressum: https://nextbricolage.github.io/qurio/impressum.html

These URLs are used in the Atlassian Developer Console → **Distribution** form
(required "Privacy policy" field) so the app can be set to **Sharing** and used
by non-owner accounts. Atlassian's standard end-user agreement covers the terms
of service, so no custom Terms page is required.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Landing page with links to the legal pages. |
| `privacy.html` | Privacy Policy. |
| `impressum.html` | Impressum (legal notice, § 5 DDG). |
| `.nojekyll` | Disables Jekyll so files are served as-is (plain static HTML). |

## Enable GitHub Pages (one-time, after first push)

1. Push this repo to `github.com/nextbricolage/qurio` on the `main` branch.
2. GitHub → repo **Settings** → **Pages**.
3. **Source**: *Deploy from a branch*. **Branch**: `main`, folder `/ (root)`. Save.
4. Wait ~1 minute, then open https://nextbricolage.github.io/qurio/privacy.html
   to confirm it is live.

## Vendor details (for the Distribution form)

- **Company / Department:** nxb labs
- **Customer support contact:** martinnxb@gmail.com
- **Privacy policy URL:** https://nextbricolage.github.io/qurio/privacy.html
- **Impressum URL:** https://nextbricolage.github.io/qurio/impressum.html
