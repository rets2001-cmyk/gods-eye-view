# Aviation Tech

A fork of [God's Eye View](https://github.com/bilawalsidhu/gods-eye-view) (MIT).

Local layers: put GeoJSON, KML or GPX files in `public/custom-layers/` and list
their file names in `public/custom-layers/manifest.json` (a JSON array). They are
imported when the globe starts. That folder is git-ignored, so the files stay on
your machine. The loader is a small block in `src/app/tools.js`.

Upstream data sources keep their own terms; see DATA_SOURCES.md.
