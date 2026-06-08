# coldstamp-site

Static site for ColdStamp — landing page + privacy policy. Served via GitHub Pages.

No build step. Plain HTML + one CSS file.

## Files

- `index.html` — landing page
- `privacy.html` — privacy policy (referenced from the Chrome Web Store listing)
- `style.css` — shared styles

## Hosting

Push to a public GitHub repo and enable Pages from `main` / root. The privacy
policy will be available at `https://<user-or-org>.github.io/coldstamp-site/privacy.html`.

When the `coldstamp.app` domain is set up as a custom domain, paths become
`https://coldstamp.app/` and `https://coldstamp.app/privacy.html`.

## Placeholders to fill before publishing

- `[OPERATOR NAME]` in `privacy.html` §1 — replace with the legal entity or
  person responsible. If you do not yet have a registered entity, your full
  legal name is fine for a v1 launch.
- `privacy@coldstamp.app` — set this up as a forwarding address (Cloudflare
  email routing or similar) before submitting to the Chrome Web Store.
