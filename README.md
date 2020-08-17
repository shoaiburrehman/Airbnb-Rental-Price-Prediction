# Airbnb Rental Price Prediction

* This is the Repository for Kaggle Competition NYC Airbnb Rental Price Prediction
* Here we did Exploratory Data Analysis, also drop the outliers and filled missing values.
* Then we plot the graphs to know in detail about this dataset.
* We also did Geospatial Analysis of this dataset.
* Then we did Feature Engineering and created dummy values.
* For our model building we used are  Linear, Ridge, Lasso, and Random Forest Regressors, Decision Tree using GridsearchCV.


## Resources We Used

* Jupyter Notebook
* We used pandas, numpy, sklearn, matplotlib, seaborn, folium packages.
* Dataset Link: https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data/notebooks


## Exploratory Data Analysis and Geospatial Analysis

* We analyzed this dataset, also drop the outliers and filled missing values so it can be usable for our model
* Then we analyzed this dataset with the help of plotting and by creating pivot table
* We also did Geospatial Analysis with scattered plotting and with the folium package.
* Then we did feature selection in Feature Engineering part.


## Model Building
* We transformed our features into dummy variables.
* We used different Models to predict the prices.
* We split this dataset into test and train set with 20% test set.
* The Random Forest model performed better than the other approaches on the test set. 

Model Used | R2 Score | MAE | RMSE 
------------ | ------------- | ------------- | -------------
Random Forest | 45.02% | 45.08 | 67.07
Decision Tree	 | 42.38% | 46.37 | 70.40
Lasso Regression	 | 39.42% | 47.97 | 70.40
Linear Regression	 | 39.42% | 47.97 | 70.40
Logistic Regression	 | 39.48% | 48.06 | 70.37
