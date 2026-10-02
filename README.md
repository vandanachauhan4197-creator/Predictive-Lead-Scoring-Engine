# Predictive Lead Scoring & Conversion Engine

A machine learning-driven web and analytics pipeline designed to evaluate inbound leads, predict conversion likelihood, and help sales teams prioritize high-value prospects.

## Project Overview
In modern digital businesses, sales teams waste countless hours on low-intent leads. This project builds a **Random Forest Classifier** model to score leads automatically based on their behavioral data, digital footprint, and form inputs.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## Project Workflow
1. **Data Preprocessing:** Handled missing values, cleaned placeholders like "Select", and dropped low-utility columns.
2. **Feature Engineering:** Converted categorical text columns into numerical format using One-Hot Encoding.
3. **Model Training:** Trained a robust **Random Forest Classifier** to spot patterns in lead behavior.
4. **Evaluation & Visualization:** Generated confusion matrices, classification reports, and plotted the **Top 10 Feature Importances** driving conversions.
5. **Model Persistence:** Saved the trained model using `joblib` (`lead_scoring_model.pkl`) for future deployment.

## Key Insights / Feature Importance
* Factors like website engagement time, lead source, and specific user choices heavily dictate whether a lead will convert.