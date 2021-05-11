# DAVE3625 - Introduction to Artificial Intelligence - Oblig 2

Ana Flávia Vital - s340046; 
Haakon Bernhard Molvig - s306458; 
Theo Alexander Sperre Olsen - s350233 

## Instructions

[Original assignment instructions available here](https://github.com/umaimehm/Intro_to_AI/tree/master/assignment2-machineLearning)

You have 10 days to work on a machine learning algorithm. I want you to pick one of the following use cases and make a prediction algorithm using either regression or classification algorithms.

Do the following:

1. Pick one use case (defined below).
2. Explore and research which algorithm would work best for this use case (regression or classification)
3. Document your findings in a ReadMe.md file (3-5 lines) on why you chose this algorithm.
4. Code the algorithm using Python
5. Keep the solution as simple as possible. We are not looking for the best machine learning algorithm. We are interested in seeing that you know how to work with machine learning.
6. Publish the code on GitHub and send us the link

You can pick one of the following use cases:

1. Predict stock market price for Norwegian airlines. I want you to make a prediction algorithm which predicts the price of this stock on a specific date. Input will be date and output should be price of that stock (close value in the data file). You should also show the predction percentage score. Data file: NAS.csv

2. Predict passenger data for Ruter Use the same data set given to you in assignment 1. I want you to make a prediction algorithm which predicts the number of passengers on a specific date for a specific bus (pick any one). Input should be date and output will be number of passengers You should also show the predction percentage score. Data file: Ruter_data.csv


## Decisions and findings
The group opted for task #1.

Since the task was to find the price, we chose a regression (as opposed to classification) algorithm. 


After some research and tests with Linear Regression and SGD, we discovered their score was around 23%; clearly not enough.
We did, however, find that Decision Tree Regression - despite it having overfit - gave us the best result with the predictions.
After testing all three (all code documented in the Jupyter Notebook file), we decided to fulfill the task with Decision Tree Regression.
