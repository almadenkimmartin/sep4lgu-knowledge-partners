# Sustainable Energy Planning for LGU Knowledge Partners

A directory of candidate knowledge partners for the DILG Local Government Academy's SEP4LGU (Sustainable Energy Planning for Local Government Units) program.

The site is one self-contained page, `index.html`, prepared by CentRE, RLI and DILG-LGA. It has five tabs, plus a floating "?" button that opens a searchable glossary of terms:

- **Directory**: every partner, with search and include/exclude filters by role, potential contribution, sector and coverage.
- **LGA Alignment and Benefit**: the same partners viewed through LGA's partnership pillars, LGRRC services and LGU capacity pillars.
- **Sustainability Map**: a 3D map of partner offices with region boundaries and elevation contours.
- **Legend**: what every filter value means.
- **Shortlist**: partners saved in your browser, with search, filters and PDF, CSV or text export.

Partner data comes from the SEP4LGU handover workbook (5 November 2026), which can be downloaded from the link under the page title.

## Data credits

- Elevation contours: produced using Copernicus WorldDEM™-90 © DLR e.V. 2010-2014 and © Airbus Defence and Space GmbH 2014-2018 provided under COPERNICUS by the European Union and ESA; all rights reserved. The organisations in charge of the Copernicus programme by law or by delegation do not incur any liability for any use of the Copernicus WorldDEM™-90.
- Region boundaries: Philippines – Subnational Administrative Boundaries, NAMRIA and PSA via OCHA/HDX, [CC BY 3.0 IGO](https://creativecommons.org/licenses/by/3.0/igo/); Negros Island Region assembled from ADM2 units per RA 12000 and PSGC, and boundaries simplified, by the SEP4LGU team. A generalized display, not an official boundary delimitation.
- Map rendering: [MapLibre GL JS](https://maplibre.org/) (BSD-3-Clause).

## Updating the site

The page is built outside this repository from the working folder's `tools/build_sustainability_map.py`. After rebuilding, run `tools/publish_site.ps1` in the working folder to copy the page here as `index.html` and push it.
