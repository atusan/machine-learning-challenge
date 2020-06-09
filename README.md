# machine-learning-challenge
This project is a part of the Data Analytics Boot Camp.

#### -- Project Status: [Completed]

## Project Intro/Objective
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
The purpose of this project is to create machine learning models(two machine leaning model built and compared) capable of classify candidate exoplanets from the raw dataset.

### Methods Used
* Machine Learning

### Technologies
* Python

## Project Description

### Data Preprocessing 
* Perform feature selection and remove unnecessary features.
* Use MinMaxScaler to scale the numerical data.
* Separate the data into training and testing data.

### Building Machine Learning Models
* model_1: SVC model. The score result for training and testing data are:

Training Data Score: 0.845
Testing Data Score: 0.841

GridSearchCV for this model
 param_grid = {'C': [1, 5, 10],
              'gamma': [0.0001, 0.001, 0.01]}

Results are:
best param: {'C': 10, 'gamma': 0.0001}
best score: 0.869
* model_2, RandomForestClassifier with number of estimators = 200

Score = 0.898 and GirdSearchCV = 0.894

The comparison shows RandomForestClassifier model works slightly better than SVC model for this project

## Needs of this project

- data processing/cleaning
- writeup/reporting

## Getting Started

# machine-learning-challenge
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
To help process this data,I tired two different machine learning models capable of classifying candidate exoplanets from the raw dataset

model_1, I used SVC model the results for training and testing data are:
Score: 0.841

GridSearchCV for this model using
 param_grid = {'C': [1, 5, 10],
              'gamma': [0.0001, 0.001, 0.01]}
Results are:
best param: {'C': 10, 'gamma': 0.0001}
best score: 0.869

model_2, I used RandomForestClassifier with number of estimators = 200
Score = 0.898 and GirdSearchCV = 0.894

The comparison shows RandomForestClassifier model works slightly better than SVC model for this project

