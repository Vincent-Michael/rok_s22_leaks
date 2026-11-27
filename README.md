# March of the Legions — S22 datamine guide v2.4

Extract the entire ZIP and open index.html in a modern browser. Original PNG assets are local in media/. The full media library is retained in the ZIP for reference, but the general gallery is no longer displayed on the website. For GitHub Pages publish the complete folder contents (index.html, media/, data and supporting files) in the repository root. No network connection is required.

Original map previews are 640 × 440; exact world coordinates and full-resolution terrain are not decoded. Four briefing video references are listed, but no actual briefing MP4 is present. A local video player allows importing a file without uploading it.

The media_index.json identifies original asset name, source bundle, dimensions, type and category. Includes 367 extracted sprites/textures plus 62 textures from multi-bundle packages. Some images are general patch art, texture sheets or UI primitives, not S22 content. Raw localization sources remain included. Original Unity .lb bundles are excluded. For GitHub Pages, upload s22-site.zip and (optionally) s22-media.zip to the repository root; the workflow extracts them. The primary package contains every PNG referenced by the HTML. The optional package contains the remaining original PNGs; extract both into the same folder for local use.

Version 2.2: all 21 resolved strategy descriptions and corrected branches/tiers from the supplied decoded configuration. Includes an interactive 16-point build planner, raw configuration fields, CSV and JSON. Original raw localization is preserved. Seize & Conquer has a daily/weekly wording conflict; reset cadence remains unverified. No new gameplay validation.


Version 2.4: six original S22 JSON exports (120 records total), 25 city/province/tile records, searchable city grid with configurable hypothetical 60×60 projection, original building and wall buff icons, and searchable raw configuration tables. Exact geographic positions, province boundaries, city levels and camp assignments remain unverified. The original map preview is unchanged.
