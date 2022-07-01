# Practical_ML_coursera

This repo is for the final assignment for the Practical Machine Learning Coursera.

For this project, I used data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants to predict how well participants performed a barbell lift. More information about the data can be found at http://groupware.les.inf.puc-rio.br/har.


In the main file (final_project.Rmd), I trained 3 different models (random forests, support vector classifier, and decision trees). I used k-fold cross-validation for each model to obtain accuracy and out of sample error rate. Based on the results, I selected the best model (random forests) to predict 20 cases in the test set. 

For the html results, you can visit https://htmlpreview.github.io/?https://github.com/vicomello/Practical_ML_coursera/blob/main/final_project.html
