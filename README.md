# credit-risk-classification
**Instructions**
The instructions for this Challenge are divided into the following subsections:

**Split the Data into Training and Testing Sets**
Open the starter code notebook and use it to complete the following steps:
Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

**Create a Logistic Regression Model with the Original Data**
Use your knowledge of logistic regression to complete the following steps:
Fit a logistic regression model by using the training data (X_train and y_train).
Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
Evaluate the model’s performance by doing the following:
Generate a confusion matrix.
Print the classification report.
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

**Write a Credit Risk Analysis Report**
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.
Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:
**An overview of the analysis: Explain the purpose of this analysis.**
The purpose of this analysis was to create a supervised machine learning model that would predict if a loan is healthy or high-risk.The data used was a 77,500 line csv file that contained columns of various data about the loan. 
Only 2,500 of the total loans were classified as high-risk.

**The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.**
balanced Accuracy Score: 95.20%
For the Healthy Loans (0), the precision is 1.00, indicating that all the predictions for this label were correct. The recall is 1.00, meaning that all instances of this label were correctly identified.
The precision for High-Risk Loan (1) is 0.85, indicating that 85% of the predictions for this label were accurate. The recall is 0.91, indicating that 91% of the instances of this label were correctly identified.
The overall accuracy of the model is 0.99, indicating that it correctly predicted the loan risk for 99% of the instances.

**A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.**
I would recommend using this model, because it has over 95% accuracy in predicting the outcome of the repayment of the initial loan. That accuracy range could be easily molded into a business risk profile to ensure sufficient capital flow for the lenders to remain in business/make a profit.
