# Project 5. Car Price Prediction


## Situation
It is necessary to take part in a team competition to predict the cost of a car by characteristics on [kaggle](https://www.kaggle.com/c/sf-dst-car-price-prediction)

Our team: Artem, Vadim, Evgeny


## Task
Imagine that you work for a company that sells used cars. The main task of the company and its managers is to find profitable offers as quickly as possible (buy below the market and sell more expensive than the market).
You need to create a model that will predict the cost of a car based on its characteristics. 
If your model works well, then you will be able to quickly identify profitable offers. This will significantly speed up the work of managers and increase the company's profit.
It is allowed to use any ML algorithms and libraries (except DL).
It is necessary to make a real ML product, which will then be able to work on new data.
There is no Train dataset for training models. Let's collect data from the site auto.ru


## Actions
1. A train dataset has been compiled from data from the site auto.ru
2. New features have been extracted and generated
3. We have tried a large number of different algorithms and ML libraries
4. Implemented Stacking
5. We performed post-processing of predictions: we introduced a correction factor that takes into account changes in the exchange rate, rounded the predicted price to 1000 rubles.


## Result
In the process of working on the project, we trained various models, the best result was shown by XGBRegressor with the parameter reg_lambda=1.5.
We managed to create a model that predicts the cost of a car based on its characteristics. This model can be used to identify profitable offers when the desired seller's price is lower than the predicted market price.


## Reflections
The strong difference in MAPE on the training and test dataset may be related to the different period of data parsing. Most learning models (excluding linear regression) showed similar results. Further improvement of the forecast can be achieved by selecting hyper parameters. Unfortunately, none of the computers were able to complete the full selection of hyper parameters in a reasonable time. In this regard, retraining on the training dataset is noticeable.
