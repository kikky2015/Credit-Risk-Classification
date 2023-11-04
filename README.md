# Credit-Risk-Classification

#Purporse of the project
This project uses various techniques to train and evaluate a model based on loan risk. Historical lending activity from a peer-to-peer lending services company was used to build a model that can identify the creditworthiness of borrowers.

* Data had to be split into training and testing Sets.
* A logistic regression model was created with the original data.
* Feature data (X_test) and the fitted model were used to save the testing data labels.
* The performance of the model was evaluated by generating a confusion matrix

## Results

* Regression model of the '0' (healthy loans):
  * The logistic regression model of the '0' (healthy loans) label has precision of 1 and recall of 0.99. This indicates the model made accurate predictions every time. 

* Regression model for the '1' (high-risk loans):
  * The logistic regression model for the '1' (high-risk loans) has a precision of 0.85 and recall of 0.91. The *model did not do a fantastic job at predicting the values for high-risk loans.

## Summary

* As compared to class 0, class 1 predictions have lower accuracy. This indicates that the model would predict loan status as healthy better than being able to predict loan status as non-healthy. Predicting healthy loans will be more important if we are only predicting those who qualify for the loans. I still recommend the model because the balanced accuracy score is 95%, which means the sensitivity (recall and/or true positive rate) and specificity (true negative rate) of the model has 95% accuracy.
