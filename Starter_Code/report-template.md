# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

*** The purpose of this analysis is to see how much we lose on higher risk loans, and help determine whether the predictability of healthy loans are enough to make up for taking on those financial risks. ***

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

                precision    recall  f1-score   support

  healthy loan       1.00      0.99      1.00     18765
high risk loan       0.84      0.94      0.89       619

      accuracy                           0.99     19384
     macro avg       0.92      0.97      0.94     19384
  weighted avg       0.99      0.99      0.99     19384

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

*** The healthy loan predictions are fantastic, with an accuracy of over 99%. However, the high-risk loan predictions are less reliable, with an accuracy of only around 84%. This indicates that the logistic regression model is better at predicting healthy loans than high-risk loans (which is to be expected). ***

If you do not recommend any of the models, please justify your reasoning.
