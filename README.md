# Python-What-s-Cooking

This project is based on the Kaggle competition,  https://www.kaggle.com/c/whats-cooking-kernels-only
The goal of the project is to predict or classify the cuisine for each recipe in the test set. 

I was able to get a prediction score of about 78%. First of all, I made a list of all unique ingredients in the data set. Then I mapped the ingredients to row Ids and created a dictionary of ingredients. I then used Logistic Regression, Decision Trees & Random Forest for finding the best model in order to get a good accuracy for prediction. 
