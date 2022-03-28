# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

Answer:

The purpose to this analysis is to validate a highly accuracte and precise predictive model using logistic regression. Utilizing Supervised Machine Learning, this analysis reviews the historical lending activity. Then, the data is split to test and train the predictive model; so, to determine the creditworthiness of the 77,536 loans.

Of the eight categories of the financial information, Loan_Status (identified as 'y') column is the data that is analyzed to predict the risk of default. 

Of the 77,536 loans, we focus in on the loan status and identify the number of good loans and bad loans (high risk of default). The value_counts function shows good loans as '0' and bad loans as '1'. There are currently 75,036 good loans and 2500 bad loans.

To perform this analysis, first stages is to read the csv file into a DataFrame. From here, extract loan_status from the dataset ;and set the labels and features (y, X). Use value_counts function to idenify how many loan are in good status or bad status. Then, to prepare the data for logistic regression, the data is split using the train_test_split function.

Two linear regression models are created: one with Original Data and another for Oversampled Data.

Methods for analysis are: Logistic Regression and RandomOverSampler to create a Resampled Training Data. 
Elaborate please


