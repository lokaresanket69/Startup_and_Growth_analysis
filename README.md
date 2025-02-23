# Startup_and_Growth_analysis


This project analyzes startup data from an Excel file to provide actionable insights on investment safety, growth forecasts, and profitability. Using machine learning models, the project makes predictions on:

- **Safe vs. Risky Investments:** Classifies startups as safe or risky based on factors like growth rate and valuation.
- **Growth Rate Prediction:** Forecasts future growth rates using regression.
- **Profitability Prediction:** Determines whether a startup is likely to be profitable or loss-making.
- **Future Valuation Forecasts:** Estimates future valuations over 5 and 10 years using compound growth formulas.

The project is implemented in Python and is designed to be run in a Jupyter Notebook.

## Features

- **Data Loading and Preprocessing:** Reads startup data from an Excel file, cleans the dataset, and prepares it for modeling.
- **Target Creation:** Generates binary target variables for safe investment and profitability, and sets up regression targets for growth rate.
- **Model Training:** Uses Random Forest classifiers and regressors to build prediction models.
- **Visualization:** Produces various plots including:
  - Stacked bar charts of safe vs. risky investments by industry.
  - A confusion matrix for the safety model.
  - Bar charts for future valuation forecasts (5-year and 10-year).
  - Profitability analysis by country.
- **Evaluation Metrics:** Outputs model accuracy, mean absolute error (MAE), and R² scores.



