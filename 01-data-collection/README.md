# Stage 01 — Data Collection

This stage collects Falcon 9 launch data from the **SpaceX API** and prepares it for analysis.

## Contents
- **`Spacex-data-collection-api.ipynb`** — Notebook with API calls, feature extraction, and cleaning.  
- **`dataset_part_1.csv`** — Cleaned dataset exported from this stage.  

## Steps
1. Fetch launch data from the SpaceX API (static snapshot for reproducibility).  
2. Enrich records with booster, payload, launchpad, and core details.  
3. Handle missing values (impute payload mass, retain `None` for landing pad).  
4. Export the cleaned dataset for the next stage.  

## Next
➡️ **Stage 02 — Web Scraping** (Wikipedia enrichment).
