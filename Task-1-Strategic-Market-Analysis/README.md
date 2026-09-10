# Strategic Market and Trend Analysis of the Apparel Industry

This project analyzes historical apparel transaction data to identify
product trends, seasonal demand patterns, customer purchasing behaviour,
and factors affecting apparel demand.

## Project Objective

To analyze historical consumer demand and market factors and demonstrate
a data-driven approach for future apparel demand forecasting.

## Analysis Performed

- Data cleaning and quality assessment
- Product-level transaction analysis
- Monthly and seasonal demand analysis
- Annual transaction trends
- Product growth analysis
- Customer transaction behaviour
- Repeat-customer product preferences
- External apparel market research
- Demand forecasting

## Forecasting

A historical-average baseline was compared with a Linear Regression model
using month and time-index features.

### Results

| Model | MAE | RMSE |
|---|---:|---:|
| Historical Average Baseline | 4.57 | 5.65 |
| Linear Regression | 3.85 | 5.06 |

The Linear Regression model performed better than the baseline on the
Jacket test period.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Dataset

Fashion Retail Sales dataset sourced from Kaggle.

The dataset is not included in this repository.
