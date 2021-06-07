# data-viz-tools

*Version: 2021-06-07*

Feature evaluation of data visualization tools

To contribute, please make a branch (e.g. named after your GitHub persona), committing to it, and issue PRs against `main` branch.

Please add tools (columns), and features (rows) as needed.

Suggested evaluation: `+` means yes, `-` means no, `n/a` means does not apply, empty means not evaluated/checked/determined yet.

| ↓ Feature / Viz Tool →                                                      | Aladin Lite   | WWT / pywwt | Firefly | Glue | ESASky | Vaex | js9 | TOPCAT | yt | add others... |
| --------------------------------------------------------------------------- | ------------- | ----------- | ------- | ---- | ------ | ---- | --- | ------ | -- | ------------- |
| **Interfaces**                                                              |               |             |         |      |        |      |     |        |    |               |
| Runs in browser                                                             |               |             |+        |      |        |      |     |        |    |               |
| Runs in notebook (e.g., via JupyterLab extension)                           |               |             |+        |      |        |      |     |        |    |               |
| Exposes API                                                                 |               |             |+ (Python, JS, HTTPS) |      |        |      |     |        |    |               |
| Scriptable (e.g. functions/buttons/menus)                                   |               |             |+        |      |        |      |     |        |    |               |
| **Image formats**                                                           |               |             |         |      |        |      |     |        |    |               |
| HiPS maps                                                                   |               |             |+        |      |        |      |     |        |    |               |
| FITS files                                                                  |               |             |+        |      |        |      |     |        |    |               |
| PNG/JPG images                                                              |               |             |+        |      |        |      |     |        |    |               |
| ADSF images                                                                 |               |             |-        |      |        |      |     |        |    |               |
| **Image layer features**                                                    |               |             |         |      |        |      |     |        |    |               |
| Measure distances and angles                                                |               |             |+        |      |        |      |     |        |    |               |
| Change quantitative stretch                                                 |               |             |+        |      |        |      |     |        |    |               |
| Change color mapping                                                        |               |             |+        |      |        |      |     |        |    |               |
| Construct three-color displays from combinations of images                  |               |             |+        |      |        |      |     |        |    |               |
| Display per-pixel Boolean bit masks as image overlay                        |               |             |+        |      |        |      |     |        |    |               |
| Image layers with controllable opacity                                      |               |             |-        |      |        |      |     |        |    |               |
| Number of supported layers                                                  |               |             |         |      |        |      |     |        |    |               |
| **Zooming and panning**                                                     |               |             |         |      |        |      |     |        |    |               |
| Zoom in/out with clickable buttons                                          |               |             |+        |      |        |      |     |        |    |               |
| Zoom in/out with mouse clicks into canvas                                   |               |             |-        |      |        |      |     |        |    |               |
| Zoom in/out with mouse wheel                                                |               |             |+        |      |        |      |     |        |    |               |
| Zoom in/out with keyboard                                                   |               |             |-        |      |        |      |     |        |    |               |
| Seamless transition from HiPS to FITS when zooming                          |               |             |+        |      |        |      |     |        |    |               |
| Pan with mouse-drag                                                         |               |             |+        |      |        |      |     |        |    |               |
| Pan with keyboard arrows                                                    |               |             |-        |      |        |      |     |        |    |               |
| **Overlays**                                                                |               |             |         |      |        |      |     |        |    |               |
| Overlay catalogs on images (see below for catalog sources supported         |               |             |+        |      |        |      |     |        |    |               |
| Display additional data associated with catalog coordinates                 |               |             |+        |      |        |      |     |        |    |               |
| Number of shown markers is progressive with zoom level                      |               |             |-        |      |        |      |     |        |    |               |
| Performance with very large number of markers                               |               |             |+        |      |        |      |     |        |    |               |
| Can a limit on number of displayed markers be configured?                   |               |             |-        |      |        |      |     |        |    |               |
| How many catalogs simultaneously?                                           |               |             |limited to server memory |      |        |      |     |        |    |               |
| Overlays on images connected to other visualizations (brushing/linking)     |               |             |+        |      |        |      |     |        |    |               |
| Displays outlines of surveys / MOCs                                         |               |             |+        |      |        |      |     |        |    |               |
| Displays outlines of instrument footprints / FOVs (and DS9-style regions)   |               |             |+        |      |        |      |     |        |    |               |
| **Mousable features (possibly web-only)**                                   |               |             |         |      |        |      |     |        |    |               |
| Click to center view                                                        |               |             |+        |      |        |      |     |        |    |               |
| Click to pop-up source/location info panel (e.g. with direct links to data) |               |             |+        |      |        |      |     |        |    |               |
| Click source marker to pop-up plot with light curve                         |               |             |-        |      |        |      |     |        |    |               |
| Click & drag to select sources (e.g. rectangle or circle)                   |               |             |+        |      |        |      |     |        |    |               |
| Selecting sources displays a table of these sources                         |               |             |+        |      |        |      |     |        |    |               |
| Currently displayed table of selected sources can be saved/exported         |               |             |+        |      |        |      |     |        |    |               |
| Rows in shown table are clickable (e.g. to pull more info from catalog)     |               |             |+ (DataLink) |      |        |      |     |        |    |               |
| Selections retrievable via API, e.g., in Python                             |               |             |+        |      |        |      |     |        |    |               |
| Can trigger callbacks in API via UI gestures (clicks, keystrokes)           |               |             |+        |      |        |      |     |        |    |               |
| **Other image display features**                                            |               |             |         |      |        |      |     |        |    |               |
| Choose coordinate system (RA+Dec, glat+glon, ...)                           |               |             |+        |      |        |      |     |        |    |               |
| Show coordinate grid                                                        |               |             |+        |      |        |      |     |        |    |               |
| Show reticle                                                                |               |             |+        |      |        |      |     |        |    |               |
| Show Healpix grid                                                           |               |             |+        |      |        |      |     |        |    |               |
| Fullscreen mode (web)                                                       |               |             |+        |      |        |      |     |        |    |               |
| Go-to-position box                                                          |               |             |+        |      |        |      |     |        |    |               |
| Name resolution in go-to box                                                |               |             |+        |      |        |      |     |        |    |               |
| Image blinking (e.g., between two layers/images), with key strokes          |               |             |-        |      |        |      |     |        |    |               |
| Image blinking (e.g., between two layers/images), with mouse gestures       |               |             |+ (& auto) |      |        |      |     |        |    |               |
| Behavior around poles (pans / doesn't pan past poles)                       |               |             |+        |      |        |      |     |        |    |               |
| **Catalog data features**                                                   |               |             |         |      |        |      |     |        |    |               |
| Select a pre-defined catalog to load                                        |               |             |+        |      |        |      |     |        |    |               |
| Perform a search via IVOA interfaces to obtain a catalog                    |               |             |+        |      |        |      |     |        |    |               |
| Upload custom catalog                                                       |               |             |+        |      |        |      |     |        |    |               |
| HiPS Catalog support                                                        |               |             |-        |      |        |      |     |        |    |               |
| Rough useful catalog size limit in rows                                     |               |             |millions |      |        |      |     |        |    |               |
| Visual filtering of catalogs (e.g., selecting regions of plots)             |               |             |+        |      |        |      |     |        |    |               |
| Text-based filtering                                                        |               |             |+        |      |        |      |     |        |    |               |
| Create catalog by clicking                                                  |               |             |-        |      |        |      |     |        |    |               |
| Create interactive plots from catalogs (X-Y, histograms, etc.)              |               |             |+        |      |        |      |     |        |    |               |
| **Add others...**                                                           |               |             |         |      |        |      |     |        |    |               |
| Browse contents of complex FITS files (mixed tables & images)               |               |             |+        |      |        |      |     |        |    |               |
