# Stage 04 — Exploratory Data Analysis (EDA) & Data Wrangling

This stage prepares the unified SpaceX Falcon 9 launch dataset for modeling by **cleaning fields, validating integrity, standardizing labels**, and **visualizing key relationships** that drive first-stage landing outcomes.

---

## 📂 Contents

- **`Space-X-DataWrangling.ipynb`** — end-to-end cleaning & standardization notebook (missing values, type fixes, label unification, feature prep).  
- **`falcon9-eda-visuals/SpaceX-EDA-Visuals.ipynb`** — visual EDA (distributions, trends, site/orbit success rates, FlightNumber × Payload analyses).

---

## 🎯 Objectives

1. Make the dataset **analysis-ready**: consistent types, tidy columns, explicit null handling.  
2. Create a **clean target** for landing success (binary/label).  
3. Explore signal in **FlightNumber**, **PayloadMass**, **Orbit**, **LaunchSite**, and **BoosterVersion**.  
4. Generate visual insights to guide **feature engineering** and later **modeling**.

---
## Output
- **`dataset_part_2.csv`** Cleaned data for visualization portion
- **`dataset_part\_3.csv`** featured engineered categorical data

---
## Next
➡️ **Stage 05 — Geospatial Analysis with folium maps for launch/landing sites**
