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






## Hints and Considerations

* Start by cleaning the data, removing unnecessary columns, and scaling the data.

* Not all variables are significant be sure to remove any insignificant variables.

* Make sure your `sklearn` package is up to date.

* Try a simple model first, and then tune the model using `GridSearch`.

* When hyper-parameter tuning, some models have parameters that depend on each other, and certain combinations will not create a valid model. Be sure to read through any warning messages and check the documentation

- - -

## Submission

* Create a Jupyter Notebook for each model and host the notebooks on GitHub.

* Create a file for your best model and push to GitHub

* Include a README.md file that summarizes your assumptions and findings.

* Submit the link to your GitHub project to Bootcamp Spot.

* Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

##### © 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
