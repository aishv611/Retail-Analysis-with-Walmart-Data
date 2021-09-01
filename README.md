# Retail Analysis with Walmart Data
## (using Python)


**In this project we focused retail analysis with Walmart data and answer the following questions:**
- Which stores have maximum and sales?
- Which store has maximum standard deviation i.e., the sales vary a lot?. Also, find out the coefficient of mean to standard deviation.
- Which store/s has good quarterly growth rate in Q3’2012?
- Find out holidays which have higher sales than the mean sales in non-holiday season for all stores together.
- Provide a monthly and semester view of sales in units and give insights.
- Build prediction to forecast demand.

There are sales data available for 45 stores of Walmart in [Kaggle](https://www.kaggle.com/aditya6196/retail-analysis-with-walmart-data). This is the data that covers sales from 2010-02-05 to 2012-11-01.

In this project, we used [RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html) and [LinearRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) to predict of sales. The data have been split into training and testing with a ratio of 80:20.
