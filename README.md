# cab-fare-prediction

## Table of contents
* [General info](#general_info)
* [Terms used](#terms_used)
* [Libraries](#libraries)

## General info
  A cab fare prediction project done by building various models and choosing the one with max. accuracy .
  The aim of the project is to explore the data read from 'train_data.csv' to analyze how the pricing works and predict the prices of data given in 'test.csv'.
  The project is sub-divided into following parts:
  1. Importing libraries
  2. Reading Data
  3. Data Overview
  4. Data Cleaning and Manipulation
  5. Analyzing the Missing Value
  6. Missing Value Imputation
  7. Outlier Analysis
  8. Feature Selection
  9. Model Development -
         a.Decision Tree,
         b.Random Forest, 
         c.Linear Regression, 
         d.KNN
  10. Predicting the fare price
  
  
## Terms used
  Haversine- The haversine formula determines the great-circle distance between two points on a sphere given their longitudes and latitudes.
  Read more at 'https://www.geeksforgeeks.org/haversine-formula-to-find-distance-between-two-points-on-a-sphere/'<br/> <br/>
  
  interquartile range (IQR)- In statistics, interquartile range (IQR) is a measure of statistical dispersion, being equal to the difference between 75th and 25th percentiles, or   between upper and lower quartiles.</br>
  IQR = Q3 −  Q1 
  Read more at 'https://online.stat.psu.edu/stat200/lesson/3/3.2' or,</br>
  'https://www.geeksforgeeks.org/interquartile-range-to-detect-outliers-in-data/'
  <br/> <br/>
  
  Quantile- Quantiles are cut points dividing the range of a probability distribution into continuous intervals with equal probabilities,
  or dividing the observations in a sample in the same way.<br/>
  Read more at 'https://en.wikipedia.org/wiki/Quantile'<br/> <br/>
  
  MAPE- The mean absolute percentage error (MAPE), also known as mean absolute percentage deviation (MAPD), is a measure of prediction accuracy of a forecasting method in statistics.</br>
   Read more at 'https://en.wikipedia.org/wiki/Mean_absolute_percentage_error'<br/> <br/>

## Libraries
    Numpy
    Pandas
    Sklearn
    Matplotlib
    Seaborn
    Missingno
    
    
