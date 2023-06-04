# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project was to compare the quality of API coverage for bike-sharing data and develop a regression model to predict bike availability at different stations.

## Process
### 1. Collected bike-sharing data from official and third-party APIs.
### 2. Cleaned and integrated the data into a merged dataset and conducted exploratory data analysis to gain insights into the dataset.
### 3. Developed a regression model to predict bike availability based on variables like empty slots, location, and ratings.
### 4. Transformed the regression model into a classification model for binary prediction of bike availability.
### 5. Evaluated the performance of the classification model using accuracy, precision, recall, and F1 score.

## Results
The CityBikes API had better coverage and more accurate data compared to the Foursquare and Yelp API's. The regression model explained 37.3% of the variance in bike availability, with the number of empty slots, location, and ratings impacting availability. The classification model had low accuracy and precision but achieved a high recall of 93.59%, capturing most instances of bike availability.

## Challenges 
Challenges included data collection from multiple APIs, handling missing values and duplicates, and modeling the complex relationship between variables.

## Future Goals
Given more time, future goals would include exploring additional data sources, improving model accuracy and precision, feature engineering and selection, and conducting extensive model validation and testing.
