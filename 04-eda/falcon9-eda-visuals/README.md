# Falcon9 Landing EDA Visuals
Analyze historical SpaceX launch data to uncover patterns that influence whether the Falcon 9 rocket’s first stage lands successfully. Since SpaceX’s cost advantage heavily depends on booster reuse, predicting landing success is key for cost estimation and mission planning.

### What Was Done

- **Exploratory Data Analysis (EDA):**  
  - Visualized the relationship between **Flight Number** and **Orbit Type**, finding that success rates improve with flight experience for Low Earth Orbit (LEO) missions, but show no clear pattern for Geostationary Transfer Orbit (GTO) missions.  
  - Explored **Payload Mass** against **Orbit Type**, revealing higher success rates for heavier payloads in Polar, LEO, and ISS orbits, while GTO orbits showed mixed results.
 
## Visualization and Plot Types

During the exploratory data analysis, the following plot types were used to understand the relationships in the data:

- **Scatter Plot with Jitter (Strip Plot):**  
  Used to visualize the relationship between **Flight Number** and **Orbit Type** with points jittered to avoid overlap, helping to observe landing success distribution across different orbits.

- **Scatter Plot:**  
  Plotted **Payload Mass** against **Orbit Type** to examine how payload weight affects landing outcomes across various orbit categories.

- **Bar Chart:**  
  Created to show the success rate of each orbit type, providing a clear comparison of landing success frequencies.

- **Line Chart:**  
  Plotted average success rate over time (by Year) to visualize trends and improvements in booster landing success as experience increased.

These visualizations were essential in identifying patterns and guiding feature selection for subsequent predictive modeling.


- **Feature Selection:**  
  - Identified key features such as Flight Number, Payload Mass, Orbit, Launch Site, booster reuse indicators, and others relevant to landing success.

- **Feature Engineering:**  
  - Applied one-hot encoding to categorical variables including Orbit, Launch Site, Landing Pad, and Serial numbers to prepare the dataset for modeling.  
  - Ensured all numeric data were consistently typed as float64 for efficient processing.

These steps laid the groundwork for building accurate predictive models in subsequent modules.

---

This analysis helps in understanding how different launch parameters and mission characteristics impact booster landing success, ultimately assisting in cost reduction and operational improvements.

