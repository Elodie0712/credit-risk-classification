# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis is to assess the effectiveness of the logistic regression model in predicting loan statuses (healthy or high-risk) based on the provided features. By splitting the data into training and testing sets, fitting the model, making predictions, and evaluating performance metrics, we can determine the model's ability to classify loans accurately and identify any potential areas for improvement.

* Explain what financial information the data was on, and what you needed to predict.

The financial information the data was on was the loan status of each loan. The data was used to predict the loan status of each loan, which included information such as whether the debt to income ration, interest rate, loan sizem borrower income, number of accounts, deregatory marsk, and total debts. 

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

![image](https://github.com/Elodie0712/credit-risk-classification/assets/148305373/217381e6-d018-44c6-9a27-8935a26ad6b9)


* Describe the stages of the machine learning process you went through as part of this analysis
.
The machine learning process included splitting the data into training and testing sets, fitting the model, making predictions, and evaluating performance metrics.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

In the provided task, logistic regression was used as the primary algorithm for building the predictive model. Logistic regression is a popular statistical method for binary classification tasks, which are tasks where the target variable has two possible outcomes. It models the probability that an instance belongs to a particular class given its features.
## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
![image](https://github.com/Elodie0712/credit-risk-classification/assets/148305373/53a82d5e-ef1e-4e9b-b12b-2e89ff7a6e46)

The balanced_accuracy score of the model: 0.9520479254722232
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:


- **Precision**: For label 0 (healthy loans), the precision is 1.00, meaning that all instances classified as healthy loans were indeed correct. For label 1 (high-risk loans), the precision is 0.85, indicating that 85% of the instances classified as high-risk loans were correct.
  
- **Recall**: For label 0, the recall is 0.99, implying that 99% of the actual healthy loans were correctly classified. For label 1, the recall is 0.91, meaning that 91% of the actual high-risk loans were correctly classified.

- **F1-score**: The F1-score is the harmonic mean of precision and recall. It provides a balance between precision and recall. The weighted average F1-score for both classes is 0.99 for label 0 and 0.88 for label 1.

- **Accuracy**: The overall accuracy of the model is 99%, which is high. It indicates that the model correctly predicted the loan status for 99% of the instances in the dataset.

Based on these metrics, the model performs exceptionally well, especially in correctly identifying healthy loans (label 0). However, there seems to be a slight imbalance in precision and recall for high-risk loans (label 1), with slightly lower precision compared to recall.

In conclusion, the model demonstrates high accuracy and performs well in predicting both healthy and high-risk loans. However, if the goal is to prioritize the identification of high-risk loans with higher precision, further tuning or adjustments may be required.
