# Stacking_Ensembling-method_-on-Titanic-Dataset
Applying Stacking (Ensembling Technique) on Titanic dataset

**Stacking:**
Stacking is a ensembling method where we use few basic machine learning models (classifiers) for predictions at first-level (base) and then uses another model at the second-level to predict the output from the earlier first-level predictions.

Here we have used Random Forest,Extra Trees,AdaBoost,Gradient Boosting and Support Vector Machines as base level(first) classifiers and then XGBoost at second level to predict the Target variable.

**Dataset Description:**

PassengerID— A column added by Kaggle to identify each row and make submissions easier

Survived— Whether the passenger survived or not and the value we are predicting (0=No, 1=Yes)

Pclass—	The class of the ticket the passenger purchased (1=1st, 2=2nd, 3=3rd)

Sex— The passenger's sex (M/F)

Age— The passenger's age in years

SibSp— The number of siblings or spouses the passenger had aboard the Titanic

Parch— The number of parents or children the passenger had aboard the Titanic

Ticket— The passenger's ticket number

Fare— The fare the passenger paid

Cabin— The passenger's cabin number

Embarked— The port where the passenger embarked (C=Cherbourg, Q=Queenstown, S=Southampton)

