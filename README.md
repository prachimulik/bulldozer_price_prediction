# bulldozer_price_prediction
We are solving regression problem of predicting the future sale price of bulldozer using Machine Learning

## 1. Problem definition:
From given characteristics and previous examples of saling price of similar bulldozers, How well (with less error) we can predict the future sale price of a bulldozer?

## 2. Data:
The data is downloaded from the Kaggle Bluebook for Bulldozers Competition.
There are 3 main datasets:
  Train.csv is the training set, which contains data through the end of 2011.
  Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012.
  Test.csv is the test data set contains data from May 1, 2012 - November 2012.

## 3. Evaluation:
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.
For more on the evaluation of this project check: https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview/evaluation.

## 4. Features
Kaggle provides a data dictionary detailing all of the features of the dataset.

### Our goal for this project will be to build a machine learning model which minimises RMSLE.
