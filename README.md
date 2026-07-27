# Lititz BMX Games

Public static-site collection for interactive Lititz BMX experiences.

## Public architecture

- `/` — Lititz BMX Games collection homepage
- `/brandon/` — **Help Brandon Hetrick Build a Pump Track in Warwick Township**

Expected initial GitHub Pages addresses:

- `https://article134-tech.github.io/lititzbmx-games/`
- `https://article134-tech.github.io/lititzbmx-games/brandon/`

A later custom domain may map the same structure to:

- `https://games.lititzbmx.com/`
- `https://games.lititzbmx.com/brandon/`

## Release structure

The approved Brandon Hetrick game is preserved byte-for-byte inside `brandon/`.
Future games should be added as their own sibling directories, each with an
`index.html` at the top of its project folder.

Example:

```text
lititzbmx-games/
├── index.html
├── assets/
├── brandon/
├── escape-rooms/
└── future-game/
```

## Status

- Collection hub: v1.0.0
- Brandon game: v1.1.0
- Custom domain: not configured in this release
