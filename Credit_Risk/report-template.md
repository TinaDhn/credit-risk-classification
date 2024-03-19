# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    Machine learning techniques are used to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
* Explain what financial information the data was on, and what you needed to predict.
    the size of the loan
    its interest rate
    the borrower's income
    the debt to income ratio
    the number of accounts the borrower held
    derogatory marks against the borrower
    the total debt
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    Split the Data into Training and Testing Sets
    Create a Logistic Regression Model with the Original Data
    Write a Credit Risk Analysis Report
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
    The dataset (77,536 data points) was split into training and testing sets. The training set was used to build an initial logistic regression model (Logistic Regression Model 1) using the LogisticRegression module from scikit-learn. Logistic Regression Model 1 was then applied to the testing dataset. The purpose of the model was to determine whether a loan to the borrower in the testing set would be low- or high-risk and results are summarized below.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
     balanced Accuracy Score: 95.20% 
     For the Healthy Loans (0), the precision is 1.00, indicating that all the predictions for this label were correct. The recall is 1.00, meaning that all instances of this label were correctly identified. 
     The precision for High-Risk Loan (1) is 0.85, indicating that 85% of the predictions for this label were accurate. The recall is 0.91, indicating that 91% of the instances of this label were correctly identified. 
     The overall accuracy of the model is 0.99, indicating that it correctly predicted the loan risk for 99% of the instances.

## Summary


Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. I would recommend using this model, because it has over 95% accuracy in predicting the outcome of the repayment of the initial loan. That accuracy range could be easily molded into a business risk profile to ensure sufficient capital flow for the lenders to remain in business/make a profit.



