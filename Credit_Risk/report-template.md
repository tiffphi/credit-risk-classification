

## Credit Report Analysis:

## Overview: 

The purpose of this analysis was to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. Class 0 indicates a healthy loan and Class 1 indicates a high-risk loan. To do this, I used a Logistic Regression model and you will see below that it performed pretty well. 


## Results:

Class 0 (Healthy loan):

Precision: 1.00
Recall: 1.00
F1-score: 1.00
This indicates that the model's predictions for healthy loans (class 0) are perfect. It correctly identifies all healthy loans in the dataset without any false positives or false negatives.

Class 1 (High-risk loan):

Precision: 0.87
Recall: 0.89
F1-score: 0.88
The precision of 0.87 suggests that when the model predicts a loan as high-risk, it is correct about 87% of the time. The recall of 0.89 indicates that the model correctly identifies about 89% of the actual high-risk loans in the dataset. The F1-score of 0.88 is a harmonic mean of precision and recall for class 1.

## Summary
In summary, the logistic regression model demonstrates excellent performance in predicting both healthy and high-risk loans. The model performs very well, achieving high precision, recall, and F1-score for both classes. It is most accurate on the healthy loans but still has an 87% precision rate in predicting high-risk loans. 

## ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
## Original Template Provided

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