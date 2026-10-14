# Limitations and verification status

**Status: public portfolio release of existing visual outputs, based on the author’s permission confirmation.** Source methods/findings and selected assets have been checked; the GIS computations and exact original input versions have not been independently reproduced or revalidated.

## What the evidence establishes

The coursework reports the Small Area counts/population sums in Table 3 and the spatial contrasts in its per-capita map. The original maps and three screenshots were visually inspected, checked for readable labels/private details and copied without edits. Their file integrity, metadata, source hashes and local documentation links were checked.

The only numerical calculation performed in this phase was bounded source consistency checking: the nominal 1.2 m/s conversion gives 360 m/720 m at five/ten minutes, and Table 3's reported sums divided by counts round to its stated means. These arithmetic checks do not verify spatial selection, population allocation or routes.

| Verification item | Status |
| --- | --- |
| Report-based claim/method checking | VERIFIED against source; still source-reported results |
| Image selection, metadata/privacy checks and unchanged asset copies | VERIFIED for selected assets |
| Documentation paths and archive exclusions | VERIFIED |
| Supplied original-project inventory | STATIC ONLY; inventory was supplied as reference, underlying project not inspected here |
| Current source-page/catalog identification | STATIC ONLY; no input snapshot or complete licence validation |
| QGIS execution, geometry repair, topology/routing and overlays | NOT RUN |
| Individual walking access and area-weighted population totals | NOT RUN / unresolved |
| Public display of the existing map outputs | Included based on the author’s confirmation; source datasets remain excluded and this is not an independent verification of correspondence |

## Method and interpretation limits

- **Population ambiguity:** p.13 describes area-weighting; p.16 Table 3 gives full population sums of intersecting Small Areas. The draft reports the latter under that definition. It does not assert the values are weighted served-population totals.
- **Thin buffers:** the coverage polygons approximate reachable network lines. They are not fully calculated walking isochrones. Buffer width and precise overlay construction are unspecified; residence-level access is unverified.
- **Mobility and network:** one nominal walking speed ignores variation with age, disability, terrain and crossings. The nine reported highway classes include primary and secondary roads. Pedestrian permissions, directionality, park access-point thinning, snapping and connectivity are not fully documented.
- **Population geography:** the uniform-within-area weighting assumption is approximate. The exact census fields, joins and study-boundary completeness are unverified. Reported subset totals should not be described as an independently confirmed city-wide census total.
- **Per-capita proxy:** `ParkM2pc` divides intersected park-fragment area attributed to a Small Area by its population and scales by 1,000. This is not a measure of actual park use, quality, visitor demand, whole-park capacity or individual exposure. Low-population areas can have large ratios.
- **Class interpretation:** the per-capita map's lowest class includes both zero and positive values. Neither exact zero counts nor individual values can be reconstructed from the raster. Zero/nonpositive-population exclusions and NULL rendering need attribute-level confirmation.
- **Data dates and boundary:** the cited parks catalog describes 2016 data; the original OSM extract date is unknown. The boundary catalog contains five local areas; exact resource/aggregation into the study mask is not established. The output is not a current-conditions inventory.
- **Quality and causality:** park facilities, maintenance, opening hours and private/semi-public green spaces were not modelled. No socioeconomic/health outcome analysis or causal equity effect is established by these maps.

## Private QA map exclusion

The QA-only population-map legend has values far above the reported 571,782 total population of the full study subset. Its field definition, units and aggregation are unresolved. The map is **excluded**, and its legend is not used as evidence of Small Area resident counts. No replacement classification, new total or silent graphical correction was made.

## Reproduction and publication boundary

QGIS was not installed or run. No geodata were downloaded, routes/isochrones calculated, routing APIs called or spatial outputs regenerated. The original large source archive/project was not retrieved. File/visual QA is separate from computational reproduction.

For any later numerical reproduction, resolve source versions/terms, boundary construction, census joins, CRS transformation, origin/network settings, buffer width, overlay/deduplication and indicator units before comparing output. This describes missing evidence, not a task performed or a request to obtain raw data now.

The author confirms public display permission for the existing map outputs. This release is not numerical validation, GIS reproduction, or a licence to redistribute raw layers. It uses selected images and documentation only.
