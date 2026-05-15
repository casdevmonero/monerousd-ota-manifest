# MoneroUSD Wallet OTA Manifests

Public GitHub Pages mirror of `latest-mac.yml` / `latest.yml` /
`latest-linux.yml` with absolute URLs pointing at the releases repo.
Custom domain: `https://update.monerousd.org`.

This repo only contains:
- `latest-mac.yml`
- `latest.yml`
- `latest-linux.yml`
- This README + a `CNAME` file

The `.gitignore` is permissive — it default-denies everything except
the OTA manifests above, so leaked wallet seeds / SSH keys / PATs /
configs cannot accidentally land here.

Source artifacts (binaries) live at
[casdevmonero/monerousd-ota-releases](https://github.com/casdevmonero/monerousd-ota-releases/releases).
