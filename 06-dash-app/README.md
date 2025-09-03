# Stage 06 — Interactive Dashboard (Dash & Plotly)

## Overview
In this stage, the Falcon 9 dataset is transformed into an **interactive web application** built with Dash and Plotly Express.  
The dashboard enables dynamic exploration of SpaceX launch outcomes by combining **dropdown filters**, **payload sliders**, and **interactive charts**.

## Contents
- **`spacex_launch_dash.py`** — Dash application script for interactive visualizations.  
- **`spacex_launch_dash.csv`** — Cleaned dataset containing payload, launch site, and outcome information.  

## Key Features
1. **Launch Site Dropdown**  
   - Filter results by a specific launch site or view aggregated results across all sites.  

2. **Success Pie Chart**  
   - For "All Sites": shows total successful launches by site.  
   - For a selected site: compares success vs failure rates.  

3. **Payload Range Slider**  
   - Adjust the payload mass range (kg) to focus the analysis.  

4. **Scatter Plot**  
   - Plots payload mass against launch outcome (success/failure).  
   - Uses color coding to distinguish **Booster Version Categories**.  

## Output
The app provides an **interactive dashboard** where users can:  
- Identify how payload range influences launch outcomes.  
- Compare site-specific performance (success vs failure).  
- Explore correlations between payload, booster version, and mission success.  


## Next ➡️ **Stage08  Ml Modeling
