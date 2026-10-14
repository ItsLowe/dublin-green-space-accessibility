# Map and workflow-evidence provenance

All six images remain **original coursework assets, not regenerated**. The three final maps and two workflow screenshots with visible OSM basemap imagery received a narrow, legible attribution strip appended beneath their original image area. No map class, legend, label, scale, analytical content or source data were changed. These five JPEGs were re-encoded to accommodate the appended credit strip; their original pixels remain visually present above it. The typology-selection screenshot does not visibly use an OSM basemap and remains byte-identical to the selected source asset. The DCC park layer used in the typology-selection screenshot is matched to the named 2016 DCC catalogue source and CC BY 4.0. Credit the dataset and do not imply DCC endorsement. Source ProjectFiles archive and QGIS layer basenames were inspected privately; source-family details remain in the public [data source note](../methodology/data_sources.md). Five OSM-backed assets carry a visible credit strip and the website caption links to the OSM copyright page. The author confirms permission for public display of all selected original map assets, including the per-capita map. Exact source snapshots, GIS calculations and item-specific licence correspondence were not independently revalidated for this release.

Cartography: Zhiheng Huang, November 2025; coursework submitted December 2025. For the maps and network previews, street data/basemap: [© OpenStreetMap contributors](https://www.openstreetmap.org/copyright), OSM data under the ODbL. Other reported sources are Dublin City Council, CSO and Ordnance Survey Ireland / Tailte Éireann; see [full attribution and reuse caveats](../methodology/data_sources.md).

## Selected assets

| Source filename | Draft file | Evidence / source-report location |
| --- | --- | --- |
| `GreenSpaceandRoad.jpg` | `figures/green_spaces_and_roads.jpg` | Green-space/street overview, p.15 Figure 7 |
| `TwoArea.jpg` | `figures/walking_accessibility_5_10_min.jpg` | Two thresholds/coverage approximation, p.16 Figure 8 |
| `Percapita.jpg` | `figures/per_capita_accessible_green_space.jpg` | Indicator choropleth, p.17 Figure 9 |
| `Typology of green spaces.jpg` | `screenshots/green_space_typology_selection.jpg` | Selection expression, p.12 Figure 3 |
| `v.grass.jpg` | `screenshots/cleaned_road_network.jpg` | Reported cleaned-network preview, p.11 Figure 2; `v.clean` named in tool table |
| `720m.jpg` | `screenshots/network_service_lines_720m.jpg` | Distinct supplied service-line preview supporting pp.12–13 methodology |

The three final maps are now 2048 × 1498 pixels (the original 2048 × 1448 map plus a 50-pixel footer strip). The credited network screenshots are 1202 × 898 and 1216 × 883 pixels; the three final maps are 2048 × 1498 pixels. The uncredited typology-selection screenshot remains 1259 × 897 pixels. JPEGs decode correctly. No EXIF/GPS entries were present. Map metadata contains standard JFIF information and a generic sRGB colour profile; screenshot metadata contains JFIF/density information and, in two cases, a generic Snipaste comment. No private identifier or machine path was found in selected pixels, metadata or OCR-assisted review.

The original internal legend labels remain in the maps. README captions explain their meaning and the time/indicator approximations without changing the source classes. The map's zero-inclusive lowest per-capita class does not establish exact zero values.

## Asset integrity after attribution update

The original image sources are documented in the archived Phase 4 staging. Current hashes are recorded in the package-level SHA-256 file manifest. The original map/workflow content above each added attribution strip is unchanged in meaning; the new JPEG files differ from their original byte hashes because the strip is part of the image file.


The current SHA-256 and byte size for each staged image are in the root `FILE_RELEASE_MANIFEST.md`.

## Excluded materials

The original coursework PDF and all rendered pages/screenshots of it are private and excluded. The QA-only population map is excluded because its legend/attribute interpretation is unresolved. The standalone `Centroid.jpg` and `360m.jpg` screenshots are not selected: the three retained screenshots already support distinct documented steps without adding redundant/interpretable-as-validated evidence.

The entire original image/reference bundle, GIS source archive, QGIS project and all raw/processed geodata remain outside the draft. No source-map pixels were digitised to create new spatial results. The selected screenshots show prior workflow evidence, not a newly executed analysis.
