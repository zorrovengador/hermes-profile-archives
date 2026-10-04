# Hermes profile archives

Public sanitized portable profile packages. Download the 10 individual `.tar.gz` assets from:
https://github.com/zorrovengador/hermes-profile-archives/releases/tag/portable-20261004T211046Z

## Public revision

`public-clean-1`: reviewed configuration, persona and procedural skills. Private identities and organization-specific references are anonymized. Credentials, memories, conversations, cron state, curator backups, hidden catalogs, cached files, and binary document/media templates are excluded. These are not full production backups; configure your own model, integrations and dependencies after importing. Some internal capability names have been anonymized.

Verify with `sha256sum -c SHA256SUMS` and import with `hermes profile import NAME.tar.gz`.

The original private packages are not published; an operator-held local backup is retained. See `manifest.json` for the inventory and checksums of the public revision. Third-party skills retain their original licensing terms; no blanket relicensing is implied.
