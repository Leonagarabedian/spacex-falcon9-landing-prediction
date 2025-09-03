# 🚀 SpaceX Falcon 9 Landing Prediction (End-to-End)

An end-to-end machine learning pipeline to predict Falcon 9 first-stage landing outcomes.  
This project unifies **8 repos** from my IBM Data Science Capstone into one cohesive portfolio project.  
It demonstrates skills in **data collection, wrangling, SQL, geospatial analysis, interactive dashboards, and ML modeling**.

---

## Project Structure

- **01-data-collection/**
  - [jupyter-labs-spacex-data-collection-api.ipynb](01-data-collection/Spacex-data-collection-api.ipynb)  
  Collects Falcon 9 data from the SpaceX API.

- **02-web-scraping/**
  - [jupyter-labs-webscraping.ipynb](02-web-scraping/Spacex-wiki-webscraping.ipynb)  
  Scrapes historical launch data from Wikipedia.

- **03-sql/**
  - [jupyter-labs-eda-sql-coursera_sqllite.ipynb](03-sql/Spacex-sql-analysis.ipynb)  
  SQL queries and analysis for launch records.

- **04-eda/**
  - [data_wrangling.ipynb](04-eda/Space-X-DataWrangling.ipynb)  
  Cleans and merges data for modeling.  
  - **falcon9-eda-visuals/**
    - [edadataviz.ipynb](04-eda/falcon9-eda-visuals/SpaceX-EDA-Visuals.ipynb)  
    Exploratory Data Analysis (visualizations).

- **05-geospatial/**
  - [folium_launch_sites.ipynb](05-geospatial/SpaceX_Launch_Location.ipynb)  
  Geospatial analysis and launch site maps with Folium.

- **06-dash-app/**
  - [spacex-dash-app.py](06-dash-app/spacex-dash-app.py)  
  Interactive Plotly Dash web app for exploring launch data.

- **07-ml-modeling/**
  - [model_training_part5.ipynb](07-ml-modeling/SpaceX_ML.ipynb)  
  Builds ML models (Logistic Regression, SVM, Decision Tree, KNN), tunes hyperparameters, and evaluates performance.

- **08-docs/**
  - Project documentation, diagrams, and slides.

---

## Features

- API & Web scraping → unified dataset  
- SQL for filtering and analysis  
- Exploratory data analysis & visualization  
- Geospatial mapping of launch sites with Folium  
- Interactive dashboard built in Plotly Dash  
- ML training with hyperparameter optimization & evaluation  
- CI/CD checks for reproducibility

---

## Tech Stack

- **Languages**: Python (pandas, numpy, scikit-learn) • SQL  
- **Visualization**: Plotly, Dash, Folium, Matplotlib  
- **Tools**: Jupyter, GitHub Actions (CI), pytest, nbval  
- **Environment**: venv/conda, requirements.txt  

---

##  Quickstart

```bash
# create virtual environment
python -m venv .venv && source .venv/bin/activate

# install dependencies
pip install -r requirements.txt

# run Dash app
cd 06-dash-app
python spacex-dash-app.py
