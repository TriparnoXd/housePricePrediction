# House Price Prediction using Simple Linear Regression

## Overview

This project demonstrates a simple linear regression model to predict house prices based on the median income feature using a California housing dataset. The notebook covers data loading, preprocessing, training the model, and evaluating its performance through visualization and statistical metrics.

## Project Details

- **Project Name:** House Price Prediction using Simple Linear Regression
- **Author:** Triparno Das
- **Institution:** SRM University, KTR M1 (BTech, First Year)
- **Club:** Club Liftoff

## Dataset

The dataset contains 3000 entries with the following columns:
- `longitude`
- `latitude`
- `housing_median_age`
- `total_rooms`
- `total_bedrooms`
- `population`
- `households`
- `median_income`
- `median_house_value`

For this project, the analysis focuses on using **median_income** as the predictor and **median_house_value** as the target variable.

## Project Structure

- **Notebook:** `HousePrice_LinearRegression.ipynb` – Contains the full implementation.
- **Dataset:** `housing.csv` – CSV file with the housing data.

## How to Run

1. **Clone or Download the Repository:**  
   Download the notebook and dataset files to your local machine or directly open the notebook in [Google Colab](https://colab.research.google.com/).

2. **Install Required Libraries:**  
   Ensure you have the following Python libraries installed:
   - numpy
   - pandas
   - matplotlib
   - seaborn
   - scikit-learn  
   You can install them via pip if needed:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
