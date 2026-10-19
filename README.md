# Qurio — public legal pages

Static pages for **Qurio — Q&A for Confluence** (published by **nxb labs**),
served via GitHub Pages at:

- Home: https://nextbricolage.github.io/qurio/
- Privacy Policy: https://nextbricolage.github.io/qurio/privacy.html
- Terms of Service: https://nextbricolage.github.io/qurio/terms.html

These URLs are used in the Atlassian Developer Console → **Distribution** form
(required "Privacy policy" / "Terms of service" fields) so the app can be set to
**Sharing** and used by non-owner accounts.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Landing page with links to the legal pages + support contact. |
| `privacy.html` | Privacy Policy. |
| `terms.html` | Terms of Service. |
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
- **Terms of service URL:** https://nextbricolage.github.io/qurio/terms.html
