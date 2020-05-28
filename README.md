# GDP-Prediction

## Data Source

We have 'Countries of The World' data set (from kaggle: Fernando Lasso: https://www.kaggle.com/fernandol/countries-of-the-world).

## Data Description

This dataset have each country as a data point (227 countries in total), and for each, we have 20 columns, each column represents a different aspect or measure of the specific country.

## Project Goal

The goal of the project is to understand this dataset, get some insights from it, and finally to train a model that can predict GDP per capita for each country.

![](/gdp_average.png)

## Conclusion

In this project, we used countries_of_the_world dataset to build a GDP predictor. 3 different learning regressors (Linear Regression, Random Forest, and XGBoost) were tested, and we have acheived the best prediction performance using Random Forest, followed by XGBoost, and then Linear Regression The best prediction performance was acheived using Random Forest regressor, using all features in the dataset, and resulted in the following metrics:

MAE: 1836.7804347826088 <br>
RMSE: 2602.8403344690837 <br>
R2_Score: 0.9185288308697308 <br>

Taking into account that the gdp_per_capita values in the dataset ranges from 500 to 55100 USD.
