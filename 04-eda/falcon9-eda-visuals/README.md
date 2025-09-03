# Stage 04 — EDA 

This stage explores patterns that affect whether the rocket’s first stage lands successfully. Since booster reuse is central to SpaceX’s cost advantage, understanding these patterns is key for prediction.

---

## What Was Done

- Standardized columns and data types (dates, numbers, categories).  
- Handled missing values and normalized landing outcome labels.  
- Explored how **Flight Number**, **Payload Mass**, **Orbit**, and **Launch Site** relate to landing success.  
- Created new features and prepared the dataset for machine learning.

---

## Visualizations

- Scatter plots of Flight Number vs. Payload Mass with landing outcomes.  
- Bar charts of success rates by Orbit and Launch Site.  
- Line charts showing landing success trends over time.  
- Distribution plots of Payload and Flight Number.

---

## Features Prepared

- Key predictors: Flight Number, Payload Mass, Orbit, Launch Site, Booster Version, and reuse indicators.  
- One-hot encoding applied to categorical variables.  
- Numeric fields standardized for consistency.

---

## Why It Matters

This stage produces an analysis-ready dataset and highlights the factors most tied to landing success. The insights here guide feature engineering and improve the accuracy of predictive models in later stages.
