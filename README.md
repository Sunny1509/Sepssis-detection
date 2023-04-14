# Sepssis-detection

## 1. Identifying problem ##

The aim of the project is to detect whether the patients in the ICU have Sepssis or not. Hence the problem belongs to the Classification category.

## 2. Loading Data and EDA ##

The data is loaded into the dataframe by using pandas and general information has been explored. The data contains 599 rows and 11 features.
The data is skewed and hence normalisation techniques such as Min-max scaler is  used to normalize the given data.
Outliers have been detected and have been removed during the process.
Correlation between the features have been displayed through the heatmap.


## 3. Data Modeling ##

For this task the problem is solved through:
1. Decission Tree
2. Random Forest Regression

## 4. Hyperparameter Tuning ##

Hyperparamter tuning has been carried out for both the models.

## 5. Evaluate Model ##

Since the problem belongs to classification category, accuracy has been used to evaluate the performance of the model.

## 6. Ultimate Judgement ##

The model is tested on the unseen data and the appropriate model to solve the task has been identified.
