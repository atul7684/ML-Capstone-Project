# Problem Statement
Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. We might have often heard travelers saying that flight ticket prices are so unpredictable. That’s why we will try to use machine learning to solve this problem. This can help airlines by predicting what prices they can maintain.

Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a predictive model which will help the customers to predict future flight prices and plan their journey accordingly.


# CHALLENGES FACED

## Data Preprocessing:
In data preprocessing, Converting the date_of_journey column to timestamp seems difficult step and converting the Duration column using timedelta function for extracting minutes and hours to find difficult to done.

## Hyperparameter Tuning:
While doing hyperparameter its trying out all the possibilities can consume a lot of computer power. Here we used RandomsearchCV to get more efficiently. It performed well but it takes a lot of time to get best parameters.
