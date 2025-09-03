# Stage 07 — Machine Learning Modeling

## Overview
In this stage, the Falcon 9 dataset is used to build **supervised machine learning models** that predict the likelihood of a successful first-stage landing.  
By applying classification algorithms and evaluating their performance, we aim to determine which model best captures the relationship between mission features (payload, orbit, site, booster version) and launch outcomes.

## Contents
- **`Spacex_ML.ipynb`** — Jupyter notebook containing feature engineering, model training, and evaluation.  
- **`dataset_part_2.csv`** **`dataset_part\_3.csv`** — Processed dataset prepared for machine learning (derived from earlier stages).  

## Key Steps
1. **Data Preprocessing**  
   - Encode categorical variables (e.g., Launch Site, Booster Version).  
   - Normalize numerical features (e.g., Payload Mass).  

2. **Feature Engineering**  
   - Select relevant predictors from the dataset.  
   - Split data into training and test sets.  

3. **Model Training**  
   - Train multiple classifiers:  
     - Logistic Regression  
     - Support Vector Machine (SVM)  
     - Decision Tree  
     - K-Nearest Neighbors (KNN)  

4. **Model Evaluation**  
   - Compare models using accuracy, precision, recall, and F1 score.  
   - Apply hyperparameter tuning (e.g., GridSearchCV) for optimization.  

## Output
- Performance comparison across different classifiers.  
- Best-performing model identified for predicting Falcon 9 landing success.  
- Insights into feature importance and their impact on outcomes.  


