# Machine_Learning_Final_Project
This is my final project in ML.
- In this project I work with data that contain if there is heart_disease or not.
  
# Modles/ Algorithm in project:
- Logistic Regression
- KNN
- AdaBoost

# Code description:
- In the begining I normalized the data and shuffle it.
- I try to running KNN and Logistic Regression, but beacuse Unbalanced data the Error Metrics is not good.
- Also when I try to running Adaboost is doesn't improve the Error Metrics beacuse the algorithm of LR has not 50%+ epsilone % of success.
- To fix the "Unbalanced data" I used in "from imblearn.under_sampling import RandomUnderSampler" that make the data close to balance.
- As the result I can see that has an improvment when I run the KNN, LR and Adaboost.
- But the improvment is very small in Adaboost beacuse the algorithm is not fitting to the data (beacuse the data is not balanced in one hundred precent).


