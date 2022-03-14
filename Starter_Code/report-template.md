# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

These tools for analysis are, in this instance used to predict either 'healthy' or 'high risk' loan applications.

* Explain what financial information the data was on, and what you needed to predict.

Financial data used was loan size, income, debt to income ratio, total number of accounts, negative marks on credit, and total debt.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

They were each weighted by the model to determin if they had value then worked though the machine learning to find assoications worth focusing on.

* Describe the stages of the machine learning process you went through as part of this analysis.

The data was split into training and testing data, then creating and fitting the data to predict values of either 'healthy' or 'high risk' loans.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

Model selction, logistical regression, random over sampleing, and balanced accuarcy score were some of the tools used for the models created.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

Here is a screenshot of the results.  The accuracy of this model was 95.2%.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

Here is a screenshot of the results. The accuracy of this model was 99.37%


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?

Both, in my view seemed to perform relativly the same, however the second model seemed to be slightly better.  Both however seemed to consistently predict the healthy loans but did less good with predictions of the high risk loans, probably needing to be scaled more appropriately.

* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

Yes it depends on if we are looking to get out more loans, or if we are looking to more concisly avoid high risk loans.  If we want more loans, then we would like the data, if we'd like to avoid more high risk loans coming in, we'd want to improve the accuracy of the high risk loans.

If you do not recommend any of the models, please justify your reasoning.
