# Housing-Prices-Detailed-Analysis
Regression problem: ML on Housing Prices

The data can be found here:
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

# A little overview of the given problem:

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges to predict the final price of each home.

# A walkthrough of what I did:

- Creative feature engineering
- Leveraged ggplot2 library to determine determine the relationship between predictors and response variable
- Dealt with skewness of predictor as well as response variable
- Removed unnecessary outliers affecting the predictions
- Ensembling of Xgboost and Lasso regression (average voting) to predict the house prices

Overall accuracy of 83.45% is achieved.
