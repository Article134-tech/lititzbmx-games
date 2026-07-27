# Validation Report — Lititz BMX Games v1.0.2

## Scope

Usability patch for the embedded Brandon Hetrick game, updating it from v1.1.0 to v1.1.1 without changing the collection or game URLs.

## Verified

- The collection hub remains published from the repository root.
- The Brandon game remains published at `brandon/`.
- A **Restart this plan** control is present on every active game stage.
- A **Return to introduction** control is present on every active game stage.
- Both destructive controls require confirmation before clearing progress.
- Restart returns the player to Stage 1 with the original metric values.
- Return to introduction clears the current plan and renders the introduction screen.
- Automatic progress saving and normal page-refresh recovery remain intact.
- The nine-stage decision sequence, final proposal, source links, print support, campaign logo, and illustrated Brandon guide remain intact.
- Automated browser interaction testing passed for restart, return to introduction, saved-stage recovery, confirmation cancellation, and a 390-pixel mobile viewport with no horizontal overflow.
- `SITE-MANIFEST.json` and `brandon/GAME-MANIFEST.json` parse successfully.
- JavaScript syntax checks pass for the collection and game scripts.
- SHA-256 checksums were regenerated for the complete package, excluding each checksum file from its own list.

## Deployment impact

This patch updates the existing files behind the same public addresses:

- `https://article134-tech.github.io/lititzbmx-games/`
- `https://article134-tech.github.io/lititzbmx-games/brandon/`
