# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results:
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

#Results derived through Analysis (Prabha Shankar)
* Machine Learning Model 1:
  *Logistic Regression with Original Data: 
    - Accuracy: 95% 
    - Precision:
        - Healthy loan (0): 100%
        - High-risk loan (1): 85%
    - Recall: 99%



* Machine Learning Model 2:
  *Logistic Regression with Resampled Data: 
    - Accuracy: 99%
    - Precision:
        - Healthy loan (0): 100%
        - High-risk loan (1): 84%
    - Recall: 99% 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? 
Based on the results above, the logistic regression model with resampled data peformed best and most accurately
* How do you know it performs best?
The precision score for predicting healthy loans (0) is the same for Model 1 and Model 2, however, there is a higher accuracy with the resampled data in Model 2 at 99%.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Yes. It is important to predict the high risk loans (1) to ensure minimal risks and reduce the number of defaulters.

If you do not recommend any of the models, please justify your reasoning. 
The logistic regression model with resampled data was recommended. 
