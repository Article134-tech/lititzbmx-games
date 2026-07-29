# Deployment Instructions — v1.5.3

## Review first

Do not deploy before Kyle confirms the corrected SC-02 image, caption, and evidence limitation in the rendered Sugar Cayne Evidence Room.

## Deployment location

Deploy the collection beneath the existing Games repository at:

```text
lititzbmx-games/escape-rooms/
```

Do not change `brandon/`.

## Recommended update path

Use the companion patch package `Lititz-BMX-Escape-Rooms-v1.5.3-evidence-alignment-update.zip`. It contains one top-level `escape-rooms` folder. Merge that folder into the existing `lititzbmx-games` repository root and replace the destination files.

## Post-push checks

1. Games hub → Digital Escape Rooms
2. Sugar Cayne → Evidence Room → SC-02
3. Confirm Vin Rock profile visual and limitation
4. Confirm SC-05 still uses the Huffy publication audit
5. Room → All rooms → Games hub
6. Brandon remains unchanged
