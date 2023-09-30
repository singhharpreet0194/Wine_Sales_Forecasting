# ABC Estate Wines Sales Analysis

## Introduction

This project focuses on the analysis and forecasting of wine sales in the 20th century for two types of wines, Sparkling and Rose, from ABC Estate Wines. The analysis involves time series data, exploratory data analysis, model building, and evaluation.

## Dataset

- [Rose.csv](Rose%20(1).csv)
- [Sparkling.csv](Sparkling%20(1).csv)

## Project Files

- [Rose Business Report](ROSE+wine+_Business+report.docx)
- [Sparkling Business Report](Sprakling+Wine+_+Business+report.docx)
- [Rose.ipynb](Rose.ipynb)
- [Sparkling.ipynb](Sparkling.ipynb)

## Project Steps

1. **Data Preparation**
   - Read the data as appropriate Time Series data and plot it.
   - Perform Exploratory Data Analysis and decomposition.

2. **Model Building and Evaluation**
   - Split the data into training and test sets (test data starts in 1991).
   - Build exponential smoothing models and other additional models.
   - Evaluate models using RMSE on the test data.

3. **Stationarity Check**
   - Check for stationarity using appropriate statistical tests and hypothesis.

4. **Automated ARIMA/SARIMA Model**
   - Build an automated version of ARIMA/SARIMA model using AIC on the training data.
   - Evaluate this model on the test data using RMSE.

5. **Model Comparison**
   - Build a table with models, parameters, and RMSE values on test data.

6. **Optimum Model Building**
   - Build the most optimum model(s) on complete data and predict 12 months into the future with confidence intervals.

## Conclusion and Recommendations

Provide findings and suggest measures for future sales based on the model built.

For detailed problem statements, refer to the provided business reports.
