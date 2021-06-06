# <span style="color:red;font-family:Helvetica"> PREDICT THE SURVIVAL OF TITANIC PASSENGERS USING ML

# Problem Statement

Make a machine learning model that will can predict the survival or the death of a given passenger based on a set of variables describing their such as age, sex, or passenger class on the boat.

# Frame of the Problem

The test set should be used to see how well our model performs on unseen data. For the test set, the ground truth for each passenger is `not provided`. It is job to predict these outcomes. For each passenger in the test set, i use the trained model to predict whether or not they survived the sinking of the Titanic. I will use **Cross-validation** for evaluating the performance.

I've two datasets are available, a `train set` and a `test set`. I'll be using the training set to build my predictive model and  i have to take the predictions on the testing set. This is a binary classification problem

# About the Datasets

There are two Data sets Provide train set and test set.<br>
Training data set has the columns:<br>
* PassengerID
* PClass
* Name
* Sex
* Age 
* Embarked
* Parch
* SibSp
* Ticket 
* Fare
* Cabin
* Survived (Target Column)<br>

Testing Dataset also having the same columns but it does not have the Survived column i.e. Target column our job is to make preditions on them

# Attributes Information

* <span style="color:red">PassengerID:</span> Individual ID of each Passenger.
* <span style="color:red">PClass:</span> Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd).
* <span style="color:red">Sex:</span> Male or Female
* <span style="color:red">Name:</span> Name of the passenger.
* <span style="color:red">Age:</span> Age of the Passenger.
* <span style="color:red">Embarked:</span> Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).
* <span style="color:red">Parch:</span> Number of Parents/Children Aboard.
* <span style="color:red">SibSp:</span> Number of Siblings/Spouses Aboard.
* <span style="color:red">Ticket:</span> Ticket Number.
* <span style="color:red">Fare:</span> Passenger Fare.
* <span style="color:red">Cabin:</span> Cabin
* <span style="color:red">Survived:</span> Survival (0 = No; 1 = Yes)

# Libraries Used 

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Sklearn
* Statistics
* Warning
* Collections

# Steps

* Importing the Essential libraries
* Loading the Data
* Perform Exploratory Data Analysis
* Detect the Outliers
* Remove the Outliers
* Check the Missing Values
* Missing Value Treatment
* Feature Extraction
* Data Visualisation(Univariate Analysis)
* Data Visualisation(Bivariate Analysis)
* Creating the Dummy Variables
* Splitting the features and target variable
* preprocess the data (Standardising the data) 
* Splitting the data into Train set and Validation set
* Fit the models using different Algorithms
* Checking the accuracy of all models
* Tuning Hyperparameters
* Ensemble Modelling
* Generating Final Predictions on the test set
  
[Predict the Survival of Titanic Passengers - Jupyter Notebook.pdf](https://github.com/devgarg9966/Predict-the-survival-of-titanic-passengers/files/6604362/Predict.the.Survival.of.Titanic.Passengers.-.Jupyter.Notebook.pdf)
