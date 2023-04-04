# SC1015-DSAI_Python
NTU SC1015 Project

## About
This is a mini-project for SC1015 (Introduction to Data Science and Artificial Intelligence), we will be focussing on the World Happiness Report 2023.

Singapore was crowned the happiest country in Asia and ranked 25th in the UN's World Happiness Report 2023. Our group decided to dive deeper to find out how Singapore achieved its ranking, through analysing which factors were the most important in deciding happiness and to build a model to predict future happiness scores.

## Contributors

School of Computer Science and Engineering

1. Dion Lim ([@dion2910](https://github.com/dion2910))
2. Marvin ([@Brloom](https://github.com/Brloom))
3. Merwyn Masagca ([@t4bles](https://github.com/t4bles))

## Table of Contents
1. Problem Formulation
2. Models Used
3. Data-driven insights and Recommendations
4. Key learning points
5. References

## Problem Formulation
-To find out which factors are the most important in predicting happiness in a country
-To find and build a model that best predicts happiness in a country

## Models Used
-Multi variate linear regression
-Multi variate linear regression with k-fold
-Random forest regression

## Data-driven insights and Recommendations
-Random tree regression has the best model amongst the three used, having the best explained varience(R^2) of 0.838 and the lowest mean squared error(MSE) of 0.204
-From our analysis of the dataset, we have found that there are 3 variables that best predict the happiness of a country, which are GDP per capita, Social Support and Healthy life expectancy at birth.
-Hence for our recommendation, Singapore should focus on these 3 variables in order to maximise the happiness of the country and if the Singapore governemnt would want to compare our performance against other countries, Random Forest regression should be used.

## Key learning points



## References
https://scikit-learn.org/stable/auto_examples/model_selection/plot_cv_indices.html#sphx-glr-auto-examples-model-selection-plot-cv-indices-py
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html#
https://www.kaggle.com/code/jnikhilsai/cross-validation-with-linear-regression
