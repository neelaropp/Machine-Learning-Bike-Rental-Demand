## Objectives
- Identify patterns in bike rentals based on season, weather, and time of day.
- Perform data preprocessing, including feature engineering and encoding.
- Compare different regression models to predict rental counts.
- Optimize model performance using hyperparameter tuning.

## Data Preparation
- **Exploratory Data Analysis (EDA)**: Identified correlations and key features.
- **Feature Engineering**: Created dummy variables for categorical data.
- **Normalization & Cleaning**: Removed redundant columns and handled missing values.

## Modeling & Evaluation
- **Linear Regression**: Baseline model to assess initial performance.
- **Decision Tree & Random Forest**: Compared performance across models.
- **Hyperparameter Tuning**: Used Randomized Search to optimize the Random Forest model.

## Results
- **Dummy encoding improved model performance**, increasing R² from **0.39 to 0.69**.
- **Random Forest outperformed other models**, achieving an **R² of 0.91** after tuning.
- **Key insights**: Higher rentals in summer, during working hours, and in clear weather.

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Regression models, Hyperparameter tuning)
- Jupyter Notebook

## Conclusion
This project demonstrates how data-driven approaches can enhance bike rental forecasting. Future improvements could include time-series analysis and deep learning models for further accuracy.
