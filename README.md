# NuvIoT Distributions

Public distribution metadata and install/update feeds for NuvIoT products.

## Layout

- `aptix/chrome/` — APTIX Chrome extension updates and installation notes.
- Future products use their own top-level directories.

Immutable signed binaries can be published as GitHub Release assets. GitHub Pages may serve HTTPS update manifests once enabled.

## Security

- Never commit CRX private signing keys (`.pem`), credentials, access tokens, or private source.
- Verify extension ID, SHA-256, and asset availability before advancing a feed.
- Preserve signing identity across versions.
- Public distribution binaries can be downloaded by anyone; managed-browser policy restricts installation, not download.

## Status

The managed Chrome self-hosted install/update experiment is pending. No CRX or live update feed is published yet.
