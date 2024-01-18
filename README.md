<h1>Credit Risk Classification Challenge</h1>

This repository contains my work for Model 20 of the UofT SCS edX Data Bootcamp.

<h2>Background</h2>
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

<h2>Instructions</h2>

The instructions for this Challenge are divided into the following subsections:

- Split the Data into Training and Testing Sets

- Create a Logistic Regression Model with the Original Data

- Write a Credit Risk Analysis Report

<h3>Split the Data into Training and Testing Sets</h3>

Open the starter code notebook and use it to complete the following steps:

- Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

- Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

- A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

<h3>Create a Logistic Regression Model with the Original Data</h3>

Use your knowledge of logistic regression to complete the following steps:

- Fit a logistic regression model by using the training data (X_train and y_train).

- Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

- Generate a confusion matrix.

- Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

<h3>Write a Credit Risk Analysis Report</h3>

Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

- An overview of the analysis: Explain the purpose of this analysis.

- The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

- A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.



