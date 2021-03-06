
# 	πΆπ±πΎ PetFinder.my Adoption Prediction


![alt text](https://vetsource.com/wp-content/uploads/2018/11/img-pet-adoption-101.jpg)





## ποΈ Motivation and Introduction

This is a classification project, we used multiple calssification models (Random Forest Classifier,Gradient Boosting Classifier,XGB Classifier), while tuning XGBoost hyperparameters using Random Search and Bayesian optimization (Optuna) and feature engineering & selection (Imputation, Discretization, OHE).
Our main goal: to predict the speed at which a pet is adopted, based on the petβs listing on PetFinder (if the profile represents a group of pets, the speed of adoption is determined by the speed at which all of the pets are adopted). The value of adoption speed is determined by how quickly, if at all, a pet is adopted. The values are determined in the following way:

0 - Pet was adopted on the same day as it was listed.

1 - Pet was adopted between 1 and 7 days (1st week) after being listed.

1 - Pet was adopted between 1 and 7 days (1st week) after being listed.

3 - Pet was adopted between 31 and 90 days (2nd & 3rd month) after being listed.

4 - No adoption after 100 days of being listed. (There are no pets in this dataset that waited between 90 and 100 days).




## π§	 Tools and Methods

 - [NumPy](https://numpy.org/)
 - [Pandas](https://pandas.pydata.org/)
 - [Seaborn](https://seaborn.pydata.org/)
 - [scikit-learn](https://scikit-learn.org/stable/)
 - [Optuna](https://optuna.org/)


## π PetFinder DataSet

The dataset was taken from  [Kaggle](https://www.kaggle.com/competitions/petfinder-adoption-prediction/overview).



## βοΈ Setup
Copy the dataset and the notebook to your google drive, and you're good to go! 
## π§βπ€βπ§ Authors

- [Lara Ben Amar](https://github.com/larushba)
- [Rina Yasiun](https://github.com/Rinayas)
- [Sharon Lavie](https://github.com/Sharronlav)


