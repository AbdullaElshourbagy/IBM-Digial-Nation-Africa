# Project Introduction

Retailer X is boutique retailer with only one physical location. They believe that their niche in the market is attributable to their unique flair of affordable,
everyday items, including health and beauty, electronics, specialty treats, and apparel.

Their marketing is mostly word-of-mouth and a “surprise value” coupon that is sent to loyalty members, and an occasional coupon that is offered in support of local 
school fundraising efforts.

The retailer has interest in growing and potentially selling their products through new channels and is looking for some direction for an expansion strategy.
They heard about analytics and want to see what it can do for them.

After facilitating a workshop with the client (Retailer X), you understand that they want to know who their customers are, and how to reach the right customers
through targeted messaging:

- They want to know what factors are associated with increased levels of spending in their stores.
- They want to know what drives participation in their coupon and loyalty programs.

You learn that Retailer X recently conducted some customer research around customer satisfaction and discovered the following information:
- They were shocked to learn that poorer than expected store experience scores were driven by the stores’ failure to have the appropriate amounts of 
   stock on the shelves to meet the demands of their customers.
- They want to ensure that if they expand and experience increased demand for their products that they have the appropriate amount of stock on hand each day.



# Objectives
By completing this skill learning journey you should be able to:

1- Regression as a supervised learning technique.
2- Linear regression models.
3- Evaluating the performance of linear regression.
4- Applying linear regression in the Python Pandas to Retailer X use case.


# Exercise Overview
As part of the business objectives that you set for Retailer X, you help Retailer X understand the factors that are associated with the increased spending of customers. Because the total spending of each customer can take any value >=0, it is a continuous variable, so you need a regression model to predict the amount that the customer spends based on the knowledge of their income, age, loyalty, household size, and other factors.

Like the previous courses “Classification” and “Cluster Analysis”, you are provided with a Jupyter Notebook file called “Exercise-Regression.ipynb” that you use to run the code lines that are provided to reproduce the output in the screen captures.



# Writing code for regression

Regression is a supervised learning model that follows the same approach as classification. These steps describe at a high level what you are implementing by using code:

1- Select the input variables and put them in to a Pandas data frame.
2- Scale all input variables to a 0 - 1 range.
3- Create an 80 - 20 training split.
4- Train a linear regression model on the training set.
5- Predict the total spending for the testing set and calculate the error between the predicted and actual values.
