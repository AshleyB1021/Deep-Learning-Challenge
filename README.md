# Charity Funding Prediction with Neural Networks

## Overview

In this assignment, I was instructed to preprocess a dataset containing information about Alphabet Soup-funded organizations and use TensorFlow to design, compile, train, and evaluate a neural network model to predict if an organization will be successful. I then optimized the model to achieve a target predictive accuracy higher than 75%.

## Step 1: Preprocess the Data

* Upload the starter file to Google Colab and follow the provided instructions to preprocess the dataset.
* Read in the charity_data.csv to a Pandas DataFrame and identify the target(s) and feature(s) for your model. Drop the EIN and NAME columns.
* Determine the number of unique values for each column and handle rare categorical variables by binning them together.
* Use pd.get_dummies() to encode categorical variables.
* Split the preprocessed data into features array, X, and target array, y, and use train_test_split to split the data into training and testing datasets.
* Scale the training and testing features datasets using StandardScaler.

## Step 2: Compile, Train, and Evaluate the Model

* Design a neural network model using TensorFlow and Keras, considering the number of input features and nodes for each layer.
* Create the first hidden layer with an appropriate activation function.
* Add a second hidden layer if necessary, and create an output layer with an appropriate activation function.
* Compile and train the model, and create a callback to save the model's weights every five epochs.
* Evaluate the model using the test data to determine the loss and accuracy.
* Save and export your results to an HDF5 file named AlphabetSoupCharity.h5.

## Step 3: Optimize the Model

* Create a new Google Colab file named AlphabetSoupCharity_Optimization.ipynb and import your dependencies.
* Read in the charity_data.csv and preprocess the dataset as in Step 1, adjusting for any modifications that came out of optimizing the model.
* Design a neural network model, adjusting for modifications to optimize the model to achieve higher than 75% accuracy.






