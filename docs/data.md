# Data access — Group 18

Group 18 is combining agency-held climate, hydrology, and community datasets to demonstrate what fast, standards-aware interoperability can look like. Use this page to keep track of the data sources, permissions, and storage locations that power our summit deliverables.

## Primary data streams

| Source | Description | Access | Notes |
|--------|-------------|--------|-------|
| NOAA Climate Data Online (CDO) | Hourly precipitation and temperature summaries for pilot watersheds. | [https://www.ncdc.noaa.gov/cdo-web/](https://www.ncdc.noaa.gov/cdo-web/) | Use the API token stored in the team password vault. Pull into `data/raw/noaa_cdo/`. |
| USGS Water Services API | Streamflow, gauge height, and discharge records for interoperability testing. | [https://waterservices.usgs.gov/](https://waterservices.usgs.gov/) | Document parameter codes in the metadata crosswalk (`documentation/metadata-crosswalk.md`). |
| Local partner datasets | Community-provided socio-ecological indicators (shared via CyVerse). | `i:/iplant/home/shared/esiil/Innovation_summit/Group_18/shared_data/` | Confirm sharing permissions before redistribution; reference data contracts in the repo. |

## Storage layout

- **Community folder:** `i:/iplant/home/shared/esiil/Innovation_summit/Group_18/`
  - `shared_data/` – canonical copies from partners.
  - `harmonized/` – outputs from automated schema mapping workflows.
  - `deliverables/` – figures, briefs, and reproducible notebooks ready for publication.
- **Local repo folders:**
  - `data/raw/` – scratch space for downloads (do not commit large files).
  - `data/processed/` – small extracts safe to version control if <50 MB.

## Access checklist

- [ ] Record API tokens or credentials in secure storage (not in Git).
- [ ] Capture provenance and licensing details in `documentation/metadata-crosswalk.md`.
- [ ] Note any restrictions in commit messages and the **Data** section of the homepage.
- [ ] When in doubt, link to authoritative sources instead of copying large files into the repo.
