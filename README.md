# Second-Hand Hyundai Grand i10 Price Prediction

This project aims to analyze the dataset containing the prices of second-hand Hyundai Grand i10 cars with respect to the year of manufacture.
The goal is to find the best linear relationship between the year and price, and then predict the possible price of a 2022 model second-hand Grand i10.
Additionally, Lasso regression is utilized to compare its performance with linear regression.


**Table of Contents**

Introduction

Dataset

Analysis and Modeling

Evaluation Metrics

Prediction

Conclusion

**Introduction**

This project involves analyzing a dataset of second-hand Hyundai Grand i10 car prices and building regression models to predict the prices based on the year of manufacture.
Linear regression and Lasso regression algorithms are employed for modeling, and their performances are evaluated using relevant metrics.


**Dataset**

The dataset contains two columns: 
'Year' representing the year of manufacture and 'Price' denoting the price of the second-hand car.
It consists of 112 entries with no missing values.


**Analysis and Modeling**

The correlation between the 'Year' and 'Price' columns is visualized using a heatmap to understand the relationship between the variables.

Linear regression and Lasso regression models are trained using the dataset to predict car prices based on the manufacturing year.

The performance of both models is evaluated using metrics such as mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE).

**Evaluation Metrics**

Mean absolute error (MAE), mean squared error (MSE), and root mean squared error (RMSE) are calculated to assess the performance of the regression models.

These metrics provide insights into the accuracy and reliability of the predictions made by the models.

**Prediction**

The trained linear regression model is used to predict the possible price of a 2022 model second-hand Grand i10 car.

The predicted price is obtained and displayed as the output of the prediction process.

**Conclusion**

Both linear regression and Lasso regression models exhibit low accuracy scores, suggesting that the dataset may not be suitable for regression analysis.
The predictions made by the models do not fit well with the existing data, indicating limitations in the dataset or the chosen modeling approach.
