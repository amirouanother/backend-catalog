# MobileMC Backend Catalog

This repository hosts the MobileMC backend catalog manifest and release assets.

## Structure

```
manifest.json          # Backend catalog manifest (served via GitHub Pages)
backends/              # Backend ZIP release assets (attached to GitHub Releases)
metadata/              # Per-renderer documentation
.github/
  workflows/
    publish.yml        # GitHub Actions: validate manifest, deploy to Pages
```

## Publishing

1. Create a GitHub release with the desired tag (e.g. `v1.1.7`).
2. Attach backend ZIP archives to the release.
3. Update `manifest.json` with the download URLs and SHA-256 checksums.
4. Push the manifest — GitHub Pages serves it at:
   `https://mobilemc.github.io/backend-catalog/manifest.json`

## Backend packages

| Renderer | Version | License | Redistributable | Download |
|----------|---------|---------|-----------------|----------|
| GL4ES | 1.1.7 | MIT | Yes | Bundled with launcher |
| MobileGlues | 1.2.8 | LGPL-2.1 | No | Official release |
| Zink | 24.2.0 | MIT | Yes | Not yet built |
| Krypton Wrapper | 0.4.5 | LGPL-3.0 | No | Official release |
| LTW | 1.0.0 | Proprietary | No | User-supplied |
| System GLES | system | n/a | Yes | Device driver |
