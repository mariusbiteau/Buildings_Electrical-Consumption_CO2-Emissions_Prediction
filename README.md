# Buildings_Electrical-Consumption_CO2-Emissions_Prediction

#### Data Source
The dataset are hosted by the City of Seattle. The city has an open data platform found here and they update their information according the amount of data that is brought in. (Update Frequency: This dataset is updated quarterly.)

(from kaggle: Fernando Lasso: https://www.kaggle.com/fernandol/countries-of-the-world).

#### Data Description
The 2 datasets (one for 2015 and one for 2016) have each building as a data point each (3340 buildings for 2015 and 3376 for 2016) and for each, we have 46 columns, each column represents a different aspect or measure of the specific building.

#### Project Goal
The goal of the project is to understand these datasets, get some insights from it, and finally to train a model that can predict the energy use and the CO2 emissions for each country. 

![]()

#### Conclusion 
4 different learning regressors (Linear Regression, Random Forest, Gradient Boosting and XGB Regressor) were tested, and we have achieved the best prediction performance using XGB Regressor, followed by Gradient Boosting, then Random Forest.

The best prediction performance was achieved with a XGB Regressor, using all features in the dataset with duplicates from 2015 and 2016 datas and some loging of the high variance features, and resulted in the following metrics:

* Mean Absolute Error (MAE): 0.2229 
* Root mean squared error (RMSE): 0.3427
* R-squared Score (R2_Score): 0.9336

![]()
