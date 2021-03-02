Objectives
By completing this skill learning journey you should be able to:

Regression as a supervised learning technique.
Linear regression models.
Evaluating the performance of linear regression.
Applying linear regression in the Python Pandas to Retailer X use case.


Exercise Overview
As part of the business objectives that you set for Retailer X, you help Retailer X understand the factors that are associated with the increased spending of customers. Because the total spending of each customer can take any value >=0, it is a continuous variable, so you need a regression model to predict the amount that the customer spends based on the knowledge of their income, age, loyalty, household size, and other factors.

Like the previous courses “Classification” and “Cluster Analysis”, you are provided with a Jupyter Notebook file called “Exercise-Regression.ipynb” that you use to run the code lines that are provided to reproduce the output in the screen captures.



Writing code for regression
Regression is a supervised learning model that follows the same approach as classification. These steps describe at a high level what you are implementing by using code:

Select the input variables and put them in to a Pandas data frame.
Scale all input variables to a 0 - 1 range.
Create an 80 - 20 training split.
Train a linear regression model on the training set.
Predict the total spending for the testing set and calculate the error between the predicted and actual values.
