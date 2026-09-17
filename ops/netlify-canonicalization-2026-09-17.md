# Netlify canonicalization beacon — 2026-09-17

Non-runtime migration marker for DV Tech repository↔deployment reconciliation.

Canonical repository: `Xinblack/xinblackmusic`
Target Netlify surface: `xinblackmusic`

This file intentionally changes no runtime behavior. A successful Git-triggered Netlify build should record this commit SHA in deploy provenance. Production is considered canonical only after the target deploy is ready and commit-attributable.
