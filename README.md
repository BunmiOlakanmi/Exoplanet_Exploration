# Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

### Description
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. This purpose of this project is to  create machine learning models capable of classifying candidate exoplanets from the raw dataset. 

### Tools used in the project
1. Python Libraries:
    - pandas
    - sklearn
    - joblib
    - matplotlib.pyplot
    - csv
    - os
3. Jupyter Notebook

### Instructions

#### Steps
The following are the steps followed for the mdoeling process:

##### Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

##### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

#### Model's Performance

* Comparison of each model's performance 
* as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).
* Model with the best performance is .... and it is saved as....

### File Description
1.  The image folder contains the image of the exoplanet used in the readme file.
2.  `DecisionTree_RandomForest.ipynb` contains the python code that builds decision tree and random forest models.
3.  `KNN.ipynb` contains the python code that builds KNN model.
4.  `Logistic_Regression.ipynb` contains the python code that builds the logistic regression model.
5.  `SVC.ipynb` contains python code that builds SVC model.
6.  `exoplanet_data.csv` is the csv file containing the raw data.
7.  `RF_MODEL.sav` is the saved random forest model file, being the best model. 
