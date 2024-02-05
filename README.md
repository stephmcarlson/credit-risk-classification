# credit-risk-classification

## Overview of the Analysis  

We are looking to analyze lending data to determine if a loan is high risk or not.  
Data we analyzed included Loan Size, Interest Rate, Income, Debt Ratio and Total Debt.  
Using this information, we were looking to predict the Loan Status column.  

In order to do this, we read in the data and split the data into a set of X with all columns except Loan Status and y which was the Loan Status column.  

Then using sklearn, we split the data into Training and Testing Data.  

We then applied a Logistic Regression model with a random state of 1 and fit the model to the training data.  
We then made testing predictions on the testing data set with the results below.  

## Results  

-Accuracy: 99%  
-Precision: 99.6% for non-high-risk; 85% for high-risk loans  
-Recall: 99% for non-high-risk; 89% for high-risk loans  

## Summary  

Overall this appears to be an accurate model and I would recommend its use. It was able to correctly identify 551 or 85% of the high risk loans. In addition to this, the model was able to correctly identify non-high risk loans at a rate of almost 100%. These two data points highlight the accuracy of the model and give confidence to its use.