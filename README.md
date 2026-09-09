# DoseGrid — legal

Hosts the support page, privacy policy and terms of use for the **DoseGrid**
iOS app, at <https://williamscott701.github.io/dosegrid-legal/>.

- [Support](https://williamscott701.github.io/dosegrid-legal/support.html)
- [Privacy Policy](https://williamscott701.github.io/dosegrid-legal/privacy.html)
- [Terms of Use](https://williamscott701.github.io/dosegrid-legal/terms.html)

These three URLs are what App Store Connect points at, so they must keep
resolving for as long as the app is on sale in any territory.

## Do not edit these pages by hand

The HTML here is generated. The source of truth is the Markdown bundled inside
the app, so the wording a user reads offline and the wording published here
cannot drift apart:

    DoseGrid/Resources/PrivacyPolicy.md
    DoseGrid/Resources/TermsOfUse.md

To publish a change, edit the Markdown in the app repository and run:

    ./scripts/publish-legal.sh

from there. It regenerates this site and pushes it.
