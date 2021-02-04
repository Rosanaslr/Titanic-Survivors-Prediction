# Titanic Survivors Prediction
Solution to kaggle competition "Tatanic - Machine Learning from Disaster" (https://www.kaggle.com/c/titanic).

## Dependencies
* Python 3
* Jupyter Notebook

## How to Run
Import `TitanicSurvivors_Prediction.ipynb` file to jupyter notebook and run.

## Solution
* Imported training dataset;
* Checked for null and duplicated data;
* Substituted outliers by median;
* Checked data distribution;
* Checked data correlation using correlation matrix;
* Selected data most likely to influence survivors;
* Splitted training dataset into train and test data;
* Trained random forest model using train data;
* Calculated accuracy score;
* Imported test dataset;
* Checked for null and duplicated data;
* Replaced null data with median;
* Predicted survivors using test dataset;
* Created submission file;