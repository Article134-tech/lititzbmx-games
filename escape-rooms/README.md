# Lititz BMX Digital Escape Rooms — v1.5.2

## Launch-Integration Navigation Patch

Six source-backed, playable digital museum experiences built from Lititz BMX artifacts, campaign records, publication captures, interviews, and collection documentation.

v1.5.2 preserves the fully reviewed v1.5.1 experience and adds the missing navigation needed to integrate the collection into the Lititz BMX Games hub.

## Experiences

- Radical Rick: The Missing Panel
- Harry’s Room: The Legacy Toolbox
- The Jersey Wall: You Are the Curator
- Backstage BMX: The Artists’ Missing BMX Connections
- Sugar Cayne: The Bike of the Day Case File
- The Greg Mathias Air Escape Room

## Navigation added

- The collection homepage now includes **← Games hub** and **Archive ↗** controls.
- Every room retains **← All rooms** and adds **Games hub**.
- Every final reveal offers both **Return to the collection** and **Return to Lititz BMX Games**.
- The 404 page provides explicit recovery links to both destinations.
- All internal return links use explicit `index.html` targets so they work under both GitHub Pages and local Windows `file:` testing.
- Footer navigation provides an additional non-blocking return path.

## Preserved behavior

- All six approved rooms and all 28 Workbench tasks are unchanged.
- All authentic images, evidence assignments, wording, and final reveals remain unchanged.
- The v1.5.1 local-progress namespace is retained so this navigation patch does not erase current saved progress.

Open `index.html` locally and test the Games hub, collection, room, final-reveal, and 404 return paths before deployment.
