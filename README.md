# Exoplanet Exploration

![](Images/exoplanets.jpg)

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. Three different  machine learning models were created to help process this data; they are capable of classifying whether a record is a candidate exoplanet from the dataset of observed objects.

## Programs Used:

* Python Pandas
* Scikit-Learn
* Keras

## Resources

* (https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

## Steps to Creating the Models:

1. Cleaning Data Frames
    * Cleaned the data.
    * Removed unnecessary columns.

2. Split Train and Test Data Sets
    * Split the data in training and testing data.

3. Normalization Data
    * Data Normalization using `MinMaxScaler`.

4. Training Process
    * Lineal Regression Model
    * SVM Model
    * Random Forest Model
    * Deep Learning Model

5. Evaluated the models
    * Identify the best score from the trained GridSearch model.
    * Made predicitons from the hypertuned model.


## Findings
* Definitely the deep learning model had the highest accuracy because it used more than one layer of hidden nodes. 

* The SVM and logistic regression models had approximately the same precision (0.87) once their GridSearchCV parameters were optimized.

* Working with the Random Forest model was really a challenge, because I used a function called RandomizedSearchCV to get the best parameters but this process took more than 1 hour to finish. Later with the optimal parameters I used the GridSearchCV function and this took more than 3 hours to finish and the result of the precision of the parameters and the prediction was very doubtful.

* The cost of time computing with the RF model was definitely worst vs. the precision of the model.

* The Deep Learning model, in addition to taking less than 1 minute to execute, obtained the best precision with a value of almost (0.89). 

### JLDA


