# Narvis Releases

This repository is the public binary distribution channel for Narvis. The
application source remains private.

- `docs/appcast.xml` is the signed Sparkle update feed served by GitHub Pages.
- GitHub Releases contain notarized, Developer ID-signed DMGs plus checksums and
  machine-readable provenance manifests.
- Published releases are immutable. A bad build is superseded by a higher
  version; release assets are never replaced in place.

Download only from this repository's Releases page or the update flow built
into Narvis. macOS verifies the app's Developer ID and notarization, while
Sparkle additionally verifies the EdDSA signature in the appcast.
