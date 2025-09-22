# Code — Interoperability prototypes

Document the key scripts, notebooks, and services that Group 18 is building during the summit. Link directly to the files in the `code/` directory (or shared cloud environments) and explain how to run them so others can replicate your steps.

## Repository layout

- `code/ingest/` — scripts that download or synchronize external datasets.
- `code/harmonize/` — notebooks and utilities that translate schemas, vocabularies, and metadata.
- `code/visualize/` — quick dashboards, plots, or reporting helpers for communicating results.
- `code/utils/` — shared helpers (configuration loaders, logging, validation) that other workflows rely on.

Feel free to adjust these folders to match how your team is organizing work.

## Workflows in progress

### Schema harmonizer notebook
- **Path:** [`code/harmonize/schema_harmonizer.ipynb`](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/code/harmonize/schema_harmonizer.ipynb)
- **What it does:** Aligns NOAA CDO climate fields with USGS Water Services metadata using a reusable translation table.
- **Inputs:** `data/raw/noaa_cdo/*.csv`, `data/raw/usgs/*.json`, and the metadata mapping in `documentation/metadata-crosswalk.md`.
- **How to run:** Launch in JupyterLab (CyVerse) and execute cells top-to-bottom; update the configuration block with date ranges and station IDs.
- **Outputs:** Harmonized dataset saved to `data/processed/interoperable_timeseries.parquet` plus summary plots saved in `docs/assets/results/`.

### Vocabulary translation CLI
- **Path:** [`code/utils/vocab_translate.py`](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/code/utils/vocab_translate.py)
- **What it does:** Applies lookup tables to remap QA/QC flags and categorical descriptors.
- **How to run:**
  ```bash
  python code/utils/vocab_translate.py \
    --config config/vocab_translation.yaml \
    --input data/raw/usgs/latest.json \
    --output data/processed/usgs_translated.json
  ```
- **Notes:** Commit updates to `config/vocab_translation.yaml` so others inherit the latest mappings.

### Visualization dashboard
- **Path:** [`code/visualize/harmonized_summary.qmd`](https://github.com/CU-ESIIL/cross-cutting-data-interoperability-harmonization-innovation-summit-2025__18/blob/main/code/visualize/harmonized_summary.qmd)
- **What it does:** Generates a Quarto dashboard comparing raw vs. harmonized feeds and highlighting anomalies.
- **Publish:** Render locally with `quarto render code/visualize/harmonized_summary.qmd --to html` and commit the HTML to `docs/assets/results/` or link to a deployed version.

## Contribution checklist

- [ ] Add a docstring or short README to every script/notebook describing purpose and inputs.
- [ ] Store credentials outside the repo (use environment variables or CyVerse secrets).
- [ ] Push intermediate results to the community folder rather than committing large binaries.
- [ ] Reference outputs on the [Home](index.md) page so partners can quickly find deliverables.

Log significant updates in [`docs/updates.md`](updates.md) to keep the sprint timeline transparent.
