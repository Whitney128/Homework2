Exoplanet Exploration

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

Preprocess the Data

Preprocess the dataset prior to fitting the model.
Perform feature selection and remove unnecessary features.
Use MinMaxScaler to scale the numerical data.
Separate the data into training and testing data.


Tune Model Parameters

Use GridSearch to tune model parameters.
Tune and compare at least two different classifiers.

Analysis

Model 1

Training Data Score: 0.8245279420179287

Testing Data Score: 0.8283752860411899

Grid Best Params: {'C': 50, 'gamma': 0.0001}

Grid Best Score: 0.8477954285797452

Model 2

Training Data Score: 0.8249094030135419

Testing Data Score: 0.8335240274599542

Grid Best Params: {'C': 100, 'max_iter': 1000}

Grid Best Score: 0.8119428536083074

After completing all requirements to come up with the training/testing data scores comparing the two models there is not much of a difference between svm and logistic regression within this dataset. 
The gridsearch was changed from gamma to max_iter in model 2 there was also not big of a change between the two.
