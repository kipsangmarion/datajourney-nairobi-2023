# Data Journey Nairobi: Carbon Emissions Prediction

## Introduction
Monitoring carbon emissions accurately is pivotal in the global fight against climate change. This competition focuses on developing machine learning or deep learning models using open-source CO2 emissions data from Sentinel-5P satellite observations to predict carbon emissions in Africa. The objective is to facilitate governments and other stakeholders in estimating carbon emission levels across the continent, especially in regions where on-the-ground monitoring is challenging.

## Competition Details
- **Start Date:** 30 June at 15:00 PM
- **End Date:** 6 July at 15:00 PM
- **Data Usage:** You are allowed to access, use, and share competition data for any commercial, non-commercial, research, or educational purposes under a CC-BY SA 4.0 license.

## Setup Instructions

### Order of Execution

1. Open the provided Colab notebook (`Carbon_Prediction.ipynb`).
2. Execute each cell sequentially:
   - Section 1: Installing and importing libraries
   - Section 2: Loading data
   - Section 3: Statistical summaries
   - Section 4: Outliers
   - Section 5: Geo Visualisation - EDA
   - Section 6: Missing values and duplicates
   - Section 7: Date features EDA
   - Section 8: Correlations - EDA
   - Section 9: Timeseries visualization - EDA
   - Section 10: Feature engineering
   - Section 11: Modelling
   - Section 10: Making predictions of the test set and creating a submission file

### Feature Explanation

1. #### location

    **Description**: This feature represents the geographical location of the region observed by the Sentinel-5P satellite.
    
    **Importance**: Latitude and urbanisation might influence carbon emissions due to increased energy consumption, affecting the accuracy of our predictions.

2. #### year and week_no

    **Description**: This feature shows when the data was collected.
    
    **Importance**: This enables us to see the change in carbon emissions over a period of time.

### Some Models one can use

1. Random Forest Regressor
2. Linear Regressor
3. KNeighbors Regressor
4. Decision Tree Regressor
5. Support Vector Regressor
6. XGB Regressor
7. CatBoost Regressor
8. Gradient Boosting Regressor
9. AdaBoost Regressor
10. Bagging Regressor
11. Light Gradient Boosting Machine(LGBM) Regressor

The best performer is the CatBost Regressor.

### Environment Setup

- Google Colab provides a pre-configured environment. Open the notebook on Colab and connect to a runtime.

### Hardware Requirements

- Google Colab provides a cloud-based environment with varying hardware specifications.

### Model Execution Time

- Execution time depends on the time taken to train a model of your choosing.

### Competition perforamce:

This project was done by a team of 2: [Shirley Ddaiddo](https://github.com/shirleymbeyu) and [Marion Kipsang](https://github.com/kipsangmarion) 

## Conclusion

Any suggestions and changes are welcome.
