# ShipLink — legal pages

Public hosting for ShipLink's Privacy Policy, Terms of Use and account-deletion
instructions. App Store Connect and Google Play both require these as public HTTPS
URLs, reachable without signing in.

**These files are generated, not written here.** The source of truth is
`services/data/legal.ts` in the ShipLink app repository, rendered by
`tools/build-legal-html.mjs`. Editing the HTML in this repository would make the
hosted copy disagree with the copy shown inside the app, which is the exact failure
the generator exists to prevent.

To update: change the app repo, run `npm run legal:html`, and copy `policies/*.html`
here.

This repository is public because the pages must be. It contains no application code.

Operated by EagLeoX LLC.
