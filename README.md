# Data Analysis Project - Fremont residential market analysis
### Overview
- Downloaded the Fremont residential data set from Bay East Association Paragon.
- Previewed the data set and performed basic cleaning on the data set.
- Engineered features, created visualization plots for features, performed exploratory data analysis.
- Utilized scikit learn to perform OLS Regression and Multiple-Linear Regression model, then use Cross-validation to evaluate model performance.

### Code and Resources Used
**Python Version**: 3.7
**Packages**: pandas, numpy,matplotlib, seaborn, sklearn

### Project Process
Section 1. Preview and Data Cleaning
  - Drop the row with missing value in BR, Bth, and YrBlt columns
  - Drop the Gar column since we have the GarSp to show if the house has garage. The column also contain input mistake.
  - Replace 'NaN' with 0 in PB, GarSp, HOA fee columns
  - Remove '$' and ',' from LP, SP, and Lot SqFt columns
  - Change LP, SP, BR, Bth, PB, GarSp, YrBlt, HOA Fee data type to 'int'

Section 2. Exploratory Data Analysis
  - Histogram, count-plot, line-plot, correlation heatmap

Section 3. Price Prediction Model
  - OLS (Ordinary Least Square)
  - Multiple linear regression
  - Cross-validation
