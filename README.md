# Load-Forecasting-for-Educational-Buildings

This repository contains the implementation and analysis for a project focused on predicting energy usage across various buildings. The dataset used is from the ASHRAE Great Energy Predictor III competition, which includes building metadata, weather data, and meter readings.

## Overview

The notebook includes:

- Data preprocessing and integration from multiple sources
- Feature engineering to enhance the predictive power of the data
- Exploratory data analysis to uncover key trends and relationships
- Initial modeling strategies for energy prediction

## Files

- `ml-project.ipynb` – Main Jupyter notebook with the complete workflow

## Steps Performed

1. Merging building, weather, and meter data
2. Cleaning and preprocessing the combined dataset
3. Creating new temporal and categorical features
4. Visualizing trends in energy usage, temperature, and time-based variables
5. Preparing the dataset for further model training (e.g., regression or time-series analysis)

## Models Used

The following models and techniques were implemented for energy prediction:

- **Decision Tree Regressor** – Used for its interpretability and handling of non-linear patterns  
- **Support Vector Machine (SVM)** – Applied for capturing complex relationships in the data  
- **Prophet** – Time series forecasting model used for trend-based energy prediction  
- **Neural Network** – Implemented for capturing higher-order interactions in the dataset  
- **LightGBM Regressor** – Gradient boosting model for optimized performance on structured data  


## How to Use

1. Clone the repository
2. Ensure all required CSV files are in the working directory
3. Open `ml-project.ipynb` in a Jupyter-compatible environment
4. Run the notebook cells sequentially to reproduce the analysis
