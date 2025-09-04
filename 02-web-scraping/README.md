# Stage 02 — Web Scraping (Wikipedia Enrichment)

This stage enriches the Falcon 9 dataset by parsing **Wikipedia tables** of launch records.  
The goal is to augment the API-derived data (from Stage 01) with additional context such as mission details, payloads, and outcomes.

## Contents
- **`Spacex-wiki-webscraping.ipynb`** — Notebook for scraping, cleaning, and normalizing Wikipedia launch tables.  

## Output
- **`spacex_web_scraped.csv`** — The cleaned dataset created from parsed Wikipedia tables.  

## Steps
1. **Fetch Wikipedia pages** containing Falcon 9 launch tables.  
2. **Extract column headers** and align with the Stage 01 schema.  
3. **Parse and clean rows** (handle footnotes, missing values, inconsistent formatting).  
4. **Add derived fields** (booster version, landing outcome, date/time split).  
5. **Convert to a DataFrame** and export as CSV.  

## Next
**Stage 03 — SQL Analysis**
