# Maternal Mortality Risk Prediction
This repository contains data and code for predicting maternal mortality risk using health indicators from 1014 pregnant women. The main focus of the project is to preprocess the data, perform feature extraction, visualize the data, and develop predictive models.

## Data Description
The dataset includes the following attributes for each observation:

Age: The age of the pregnant woman.
Systolic Blood Pressure: The systolic blood pressure measurement.
Diastolic Blood Pressure: The diastolic blood pressure measurement.
Blood Glucose: The blood glucose level.
Body Temperature: The body temperature.
Heart Rate: The heart rate.
Risk Level: The categorized risk level for maternal mortality (target variable).
Project Structure


## Scripts

### data_preprocessing.py:

Loads the data from MaternalDataset.csv.
Transforms categorical risk levels into numerical values.
Checks for and reports missing values.
Standardizes the data by subtracting the mean and dividing by the standard deviation for each attribute.

### statistics.py:

Computes and prints summary statistics for the dataset, including mean, variance, standard deviation, range, minimum, and maximum values.
Calculates the mode of the risk level attribute.

### project1.py:

Visualizes the pairwise relationships between attributes using scatter plots.
Applies Principal Component Analysis (PCA) to reduce dimensionality and visualize data in the principal component space.
Generates histograms and boxplots for each attribute to understand their distributions and identify outliers.
Computes and visualizes the correlation matrix to analyze relationships between attributes using a heatmap.
