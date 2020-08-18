# Time-Series-Modelling-UN-Millenium-Development-Goals
 Using ML techniques to forecast UN MDGs  

This is an ongoing project. I seek to uncover the best predictors of a nation's development through correlation analysis and multivariate time series
modelling using python and Tensorflow. The hope is that finding which macroeconomic indicators are the best predictors could theoretically provide
insight to the UN and specific nations about which obstacles they need to overcome to progress economically, technologically, and for the overall 
well-being of their populations. 

In this project, some techniques I use include:

 - Data Wrangling using Pandas
 
 - Initial Feature Selection using Pearson Correlation 
 
 - Data Normalization/Standardization 
 
 - Multivariate Data Imputation using K Nearest Neighbor Imputation, Iterative Imputation and Linear Time Interpolation
 
 - Multivariate Time Series Forecasting using 1D CNNs, RNNs (LSTMs), and ARIMA
 
 - Predictive modelling using Regression Analysis (KNeighbors, Linear, Logistic) Decision Trees/Random Forests
 
 Some thoughts on this project:
 
 In an ideal scenario, I'd have a more  complete dataset. That way, if I measured the correlation among the same set of  variables for each country independently, 
I'd be able to say wether the same corr's exist independent of the country. Only then could I really say that a model can be built  which can predict outcomes from the same
set of variables for any given country. If they don't match up, I believe this would mean that the variables are not enough to explain development, or rather that development 
can not be generally explained by a set of variables. It can, however, adequately enough describe the system of national dev that it can be used within a certain level of 
confidence to classify, predict, etc.


 
