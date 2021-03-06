# Predicting-the-outcome-of-a-basketball-shot

- Author:Yang Liu, Haitao Liu, Jiawei Xue<br>
- Contact: eric.liu.249@gmail.com, yliu249@stevens.edu 

## Introduction

Basketball teams spend a lot of money on training players as well as hiring coaches and specialists to win games. Typically, coaches and specialists rely on judgment and common statistics to make decisions. Sometimes this method is effective, however, sometimes it is not, because different players have different shooting habits and there are too many metrics that may affect the outcome of a shot: made or missed. Now the basketball teams have urgent demand to leverage other techniques to help them make better game strategies and train their players more efficiently.

According to this demand, we intended to implement machine learning method to predict whether a shot is going to be made or not. We took four steps in this research. First, we used the 2014-2015 NBA season shot records as our dataset and evaluated it. Second, we performed six steps for data processing and preparation: One hot encoding, handling missing values, detecting the outliers, identifying the relationships between variables, standardizing the data, and splitting the dataset. Third, we attempted to use principal components analysis to reduce dimension.  After that, we built six models based on linear discriminant analysis, logistic regression, K nearest neighbors, naïve Bayes, XGBoost and ensemble algorithm. The model results indicated that the ensemble method showed a significant enhancement over other simple algorithms, and the XGBoost had the best prediction performance. The coefficients of the models also indicated that the shooting distance and the closest defender distance are the most important metrics that affect the outcome of a shot.


