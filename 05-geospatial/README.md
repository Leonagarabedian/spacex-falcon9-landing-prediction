# Stage 05 — Interactive Visual Analytics (Folium)

## Overview
This stage extends the Falcon 9 exploratory analysis with **interactive geospatial visualizations** using Folium.  
While previous stages (Matplotlib/Seaborn) focused on statistical relationships between payload, orbit, and outcomes, here the emphasis is on **geography** — how launch site locations and proximities relate to mission success.

## Contents
- **`SpaceX_Launch_Site.ipynb`** — Jupyter notebook containing Folium-based visualizations of launch sites and outcomes.  
- **`spacex_launch_geo.csv`** — Augmented dataset with latitude and longitude coordinates for each launch site.  

## Key Tasks
1. **Map Launch Sites**  
   - Plot all SpaceX launch locations on an interactive map.  
   - Highlight each site with circles and labeled markers.  

2. **Visualize Launch Records**  
   - Add markers for every launch record (green = success, red = failure).  
   - Use **marker clustering** to handle overlapping points.  

3. **Distance Analysis**  
   - Calculate proximities between launch sites and nearby features (e.g., coastline, cities, infrastructure).  
   - Explore how geography might influence launch feasibility and recovery.  

## Output
The notebook produces interactive Folium maps that reveal **spatial patterns** in launch site usage and mission outcomes. These maps complement earlier statistical analysis by adding a **geographical perspective** to Falcon 9 launch success.

## Next
**Stage 06 — Dash App**
