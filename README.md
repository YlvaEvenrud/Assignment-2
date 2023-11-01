# Assignment-2 Machine Learning
Assignment 2 for tesla use case. Ylva Evenrud (s364748) og Siri Berg-Johnsen (s367435)

Make a prediction algorithm using either regression or classification algorithms.
Do the following:

Pick one use case (defined below).
- Tesla, predict stock price on a specific date 

Explore and research which algorithm would work best for this use case (regression or classification) 
- Regression would be best. Regression models are often use to predict continuous numeric values, as stock markets → Price(close) in tesla stock


Document your findings in a file (3-5 lines) on why you chose this algorithm. 
- We choose a regression type of machine learning because the stock market prices are continuous values. The regression algorithm we chose is Linear Regression.
- We chose this because the regression algorithm is used with continuous values, and it is most used on prediction of stock markets. The linear regression also always has an
  input (X) and output (y) variable, which fits this case. Our input variable is the specific date and outcome is the close price for this date. 

Train the algorithm using Python 
- We trained the model for a linear prediction


Keep the solution as simple as possible. We are not looking for the best machine learning algorithm. We are interested in seeing that you know how to work with machine learning. 
Publish the code on GitHub and send us the link 

You can pick one of the following use cases:
Predict stock market price for TESLA. I want you to make a prediction algorithm which predicts the price of this stock on a specific date. Input will be the date and output should be the pric of that stock (close value in the data file). You should also show the prediction percentage score. Data file: TESLA.csv For updated csv file, please download the data from: https://finance.yahoo.com/quote/TSLA/history?p=TSLA
