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
| Runs in notebook                                                            |               |             |+        |      |        |      |     |        |    |               |
| Exposes API                                                                 |               |             |+        |      |        |      |     |        |    |               |
| Scriptable (e.g. functions/buttons/menus)                                   |               |             |+        |      |        |      |     |        |    |               |
| **Image formats**                                                           |               |             |         |      |        |      |     |        |    |               |
| HiPS maps                                                                   |               |             |+        |      |        |      |     |        |    |               |
| FITS files                                                                  |               |             |+        |      |        |      |     |        |    |               |
| PNG/JPG images                                                              |               |             |+        |      |        |      |     |        |    |               |
| **Image layer features**                                                    |               |             |         |      |        |      |     |        |    |               |
| Image layers with controllable opacity                                      |               |             |-        |      |        |      |     |        |    |               |
| Number of supported layers                                                  |               |             |         |      |        |      |     |        |    |               |
| **Zooming and panning**                                                     |               |             |         |      |        |      |     |        |    |               |
| Zoom in/out with clickable buttons                                          |               |             |+        |      |        |      |     |        |    |               |
| Zoom in/out with mouse clicks into canvas                                   |               |             |-        |      |        |      |     |        |    |               |
| Zoom in/out with mouse wheel                                                |               |             |+        |      |        |      |     |        |    |               |
| Zoom in/out with keyboard                                                   |               |             |-        |      |        |      |     |        |    |               |
| Seamless transition from HiPS to FITS when zooming                          |               |             |+        |      |        |      |     |        |    |               |
| Pan with mouse                                                              |               |             |-        |      |        |      |     |        |    |               |
| Pan with keyboard arrows                                                    |               |             |-        |      |        |      |     |        |    |               |
| **Overlays**                                                                |               |             |         |      |        |      |     |        |    |               |
| Select a pre-defined catalog to overlay                                     |               |             |+        |      |        |      |     |        |    |               |
| Upload custom catalog to overlay                                            |               |             |+        |      |        |      |     |        |    |               |
| Number of shown markers is progressive with zoom level                      |               |             |-        |      |        |      |     |        |    |               |
| Performance with very large number of markers                               |               |             |+        |      |        |      |     |        |    |               |
| Can a limit on number of displayed markers be configured?                   |               |             |-        |      |        |      |     |        |    |               |
| How many catalogs simultaneously?                                           |               |             |limited to browser memory         |      |        |      |     |        |    |               |
| Displays outlines of surveys / MOCs                                         |               |             |+        |      |        |      |     |        |    |               |
| Displays outlines of instrument footprints / FOVs                           |               |             |+        |      |        |      |     |        |    |               |
| **Mousable features (possibly web-only)**                                   |               |             |         |      |        |      |     |        |    |               |
| Click to center view                                                        |               |             |+        |      |        |      |     |        |    |               |
| Click to pop-up source/location info panel (e.g. with direct links to data) |               |             |+        |      |        |      |     |        |    |               |
| Click source marker to pop-up plot with light curve                         |               |             |-        |      |        |      |     |        |    |               |
| Click & drag to select sources (e.g. rectangle or circle)                   |               |             |+        |      |        |      |     |        |    |               |
| Selecting sources displays a table of these sources                         |               |             |+        |      |        |      |     |        |    |               |
| Currently displayed table of selected sources can be saved/exported         |               |             |+        |      |        |      |     |        |    |               |
| Rows in shown table are clickable (e.g. to pull more info from catalog)     |               |             |-        |      |        |      |     |        |    |               |
| **Other features**                                                          |               |             |         |      |        |      |     |        |    |               |
| Choose coordinate system (RA+Dec, glat+glon, ...)                           |               |             |+        |      |        |      |     |        |    |               |
| Show coordinate grid                                                        |               |             |+        |      |        |      |     |        |    |               |
| Show reticle                                                                |               |             |+        |      |        |      |     |        |    |               |
| Show Healpix grid                                                           |               |             |+        |      |        |      |     |        |    |               |
| Fullscreen mode (web)                                                       |               |             |+        |      |        |      |     |        |    |               |
| Go-to-position box                                                          |               |             |+        |      |        |      |     |        |    |               |
| Name resolution in go-to box                                                |               |             |+        |      |        |      |     |        |    |               |
| Image blinking (e.g. between to layers/images), with key strokes            |               |             |-        |      |        |      |     |        |    |               |
| Behavior around poles (pans / doesn't pan past poles)                       |               |             |+        |      |        |      |     |        |    |               |
| **Add others...**                                                           |               |             |         |      |        |      |     |        |    |               |
|                                                                             |               |             |         |      |        |      |     |        |    |               |
