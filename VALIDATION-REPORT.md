# Validation Report — Lititz BMX Games v1.1.1

## Scope

Corrective collection-hub update that retains the approved v1.1.0 visual integration while fixing Windows local-file navigation before commit.

## Verified

- The hub links explicitly to `escape-rooms/index.html` and `brandon/index.html`.
- Both target entry files exist in the established repository architecture.
- Explicit `index.html` links work under the local Windows `file:` review path and remain valid under GitHub Pages.
- The patch contains only the seven established root-hub replacement files: `index.html`, `assets/styles.css`, `README.md`, `RELEASE-NOTES.md`, `SITE-MANIFEST.json`, `VALIDATION-REPORT.md`, and `SHA256SUMS.txt`.
- No file inside `brandon/` is included or modified.
- No file inside `escape-rooms/` is included or modified.
- The Escape Rooms card retains six authentic preview images already present in the approved v1.5.1 deployment.
- The existing Brandon logo, illustrated guide, exact title, card copy, and metadata remain unchanged.
- The collection status remains 7 playable experiences across 2 published collection entries.
- `SITE-MANIFEST.json` parses successfully and records both approved releases and their explicit hub entry files.
- Static HTML checks confirm one page title, one main landmark, unique IDs, two playable collection cards, and alt text on every informative image.
- Static CSS parsing completed without syntax-level parse errors.
- The complete repository checksum ledger contains 125 entries: all repository files except the root checksum file itself.
- ZIP integrity testing passed, and the ZIP contains only the seven intended replacement files.

## Manual review status

- PASS — Hub hero and both collection cards rendered correctly in Kyle’s local repository.
- FAIL FOUND / CORRECTED — v1.1.0 directory-style card links opened a local directory index in Microsoft Edge. v1.1.1 uses explicit entry files.
- REQUIRED — Re-test both buttons locally after installing this correction, then commit only after both experiences open normally.

## Deployment impact

This patch updates the existing collection homepage and repository documentation behind the same public addresses:

- `https://article134-tech.github.io/lititzbmx-games/`
- `https://article134-tech.github.io/lititzbmx-games/escape-rooms/`
- `https://article134-tech.github.io/lititzbmx-games/brandon/`

A public GitHub Pages confirmation is still required after the patch is committed and pushed.
