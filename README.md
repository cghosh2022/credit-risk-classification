# credit-risk-classification
In this Challenge, we use various techniques to train and evaluate a model based on loan risk. We used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Split the Data into Training and Testing Sets
Read the data from the CSV file into a Pandas DataFrame.
Created the labels - set y from the “loan_status” column, and then created the features DataFrame named X from the remaining columns.
NOTE: A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Then split the data into training and testing datasets by using train_test_split.
Create a Logistic Regression Model with the Original Data
Fitted a logistic regression model by using the training data (X_train and y_train).
Saved the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
Evaluated the model’s performance by doing the following:
Calculated the accuracy score of the model.
Generated a confusion matrix.
Printed the classification report.
Answered the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
Write a Credit Risk Analysis Report
Then wrote a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. The analysis was divided into following structure-

An overview of the analysis: Explaining the purpose of this analysis.
The results: Using a bulleted list, describing the accuracy score, the precision score, and recall score of the machine learning model.
A summary: Summarizing the results from the machine learning model. Including the justification for recommending the model for use by the company.