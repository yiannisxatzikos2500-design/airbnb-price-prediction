#Airbnb Price Prediction

This project develops a predictive model for Airbnb listing prices in Copenhagen, Denmark. It utilizes the Inside Airbnb dataset and implements a full data science workflow from automated data ingestion to hyperparameter tuning.

## Project Overview
The goal is to provide accurate price estimates for property listings based on features like location (latitude/longitude), property type, and guest amenities.

### Key Features:
- **Data Ingestion:** Automatically downloads the latest Copenhagen listings data.
- **Preprocessing:** Uses `ColumnTransformer` and `Pipeline` for robust handling of numerical, categorical, and boolean features.
- **Modeling:** Compares multiple algorithms:
  - Baseline (Mean Predictor)
  - Ridge Regression
  - Random Forest
  - XGBoost
- **Optimization:** Hyperparameter tuning performed via **Optuna**.
- **Geospatial Analysis:** Visualizes price distribution using **Folium** and calculates distances with **Geopy**.

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/copenhagen-airbnb-price-prediction.git](https://github.com/YOUR_USERNAME/copenhagen-airbnb-price-prediction.git)
