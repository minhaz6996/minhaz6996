# MEH Executive Overview

**Category:** Healthcare operations / management reporting  
**Tool:** Microsoft Power BI  
**Source examined:** `MEH Daily Update Dashboard.pbix` (report layout metadata only)

![Illustrative project graphic](../../assets/meh-case-study.svg)

## Project overview

A Power BI executive overview designed to consolidate selected hospital operations indicators into a single report page. The inspected report is labeled **MEH Executive Overview**.

## What the PBIX report structure shows

- **Operational KPI cards:** total OPD, total refraction, total surgery, phaco surgery, IOL surgery, DCR surgery, other surgery, and child cataract surgery.
- **Comparisons:** two clustered bar-chart visuals comparing surgery-related activity by hospital.
- **Detailed reporting:** a matrix-style visual with hospitals as rows and several measures.
- **Interactive selections:** hospital and month slicers.
- **Dashboard titles:** dynamic title/subtitle measures are present.

The PBIX definition contains one report page and 15 visuals, including KPI cards, bar charts, a matrix, and slicers. This is a report-structure observation, **not a live validation** of calculations or business results.

## Questions the dashboard is intended to support

1. How does reported service activity compare across hospitals?
2. How do surgery-related indicators change when a month is selected?
3. Which summary KPIs are available for an executive view?

## Portfolio approach and confidentiality

The original `.pbix` contains an embedded data model and may include sensitive operational information. It has **not** been added to this public-ready repository. This case study intentionally omits actual KPI values, hospital names, patient records, and source files. The graphic above is an **illustration, not a screenshot**.

If approved by the data owner, add a sanitized Power BI screenshot (with names, values, tooltips, and metadata reviewed) under `assets/` and update this case study.

## Validation status

- ✅ PBIX archive can be read; report layout and visual types inspected.
- ✅ KPI names and slicer dimensions confirmed in report definition.
- ⬜ Measures and numerical outputs not tested in Power BI Desktop.
- ⬜ Business ownership/publication approval not confirmed.

[← Back to profile portfolio](../../README.md)
