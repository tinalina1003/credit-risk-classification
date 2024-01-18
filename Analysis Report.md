<h1>Credit Risk Classification Report</h1>

<h2>Overview of the Analysis</h2>

<h3>Purpose</h3>
The dataset used is a historical lending activity from a peer-to-peer lending services company to build a model that can identify creditworthiness of borrowers. 

<h3>Dataset Information</h3>
The data includes financial information of the borrowers including loan size, interest rate, borrower's income, total debt, loan status etc. The datasize has 77536 borrowers with
75036 having healthy loan statuses and 2500 with high-risk loan status. 

<h3>Process and Methods</h3>
The process uses supervised learning algorithms from SciKit specifically the Train-Test-Split model. The methods used was to split the data into training and testing data and fit it to a logistic regression model using random_state = 1.
After the first predictions were made, a second prediction was made using imbalanced-learn library to resample the data. The data produces a new model and was fitted to a logistic regression model once again.

<h2>Results<h/2>

<h3>Machine Learning Model 1:</h3>

- Balanced Accuracy Score: 96%
- Accuracy: 100%
- Healthy Loan Precision: 100%
- Healthy Loan Recall: 99%
- High-risk Loan Precision: 85%
- High-risk Loan Recall: 91%



<h3>Machine Learning Model 2 (Resampled):</h3>

- Balanced Accuracy Score: 
- Accuracy: 100%
- Healthy Loan Precision: 100%
- Healthy Loan Recall: 99%
- High-risk Loan Precision: 85%
- High-risk Loan Recall: 91%



<h2>Summary</h2>


The first model predicted both the healthy and high-risk loans quite well. There is a 99% accuracy meaning it was able to predict almost all correct number of 0s and 1s. Furthermore, 
the model was able to accurately predict all healthy loans (100%) while the high-risk loans were a little less precise with only 85%. The model was able to almost predict all healthy loans correctly with 99% 
recall while the high-risk loans were a little less with 91% recall. Overall, the model is a good model with predicting healthy loans but not as good with high-risk loans.

The new logistic regression model fit better than the original. Both original and the new model has an accuracy of 99% with the same 100% precision for healthy loans and same 99% recall for healthy loans. 
However, the new model has a slight decrease in precision for high-risk loans but with a 99% recall for high-risk loans which was a 9% increase. Overall, this new model is much better at predicting the correct healthy and high-risk loans than the original.


In summary, I would recommend using the second model as accuracy and precision were both similar but the recall (the one that matters most) was ~10% higher. Performance does depend on the problem we are trying to solve as money is at risk. For this assignment,
it is much more important to be able to predict the correct 1's as those are where the money is most at risk.