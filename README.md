# machine-learning-challenge
This project is a part of the Data Analytics Boot Camp projects.

#### -- Project Status: [Completed]

## Project Intro
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
The purpose of this project is to create machine learning models(two machine leaning model built and compared) capable of classify candidate exoplanets from the raw dataset

### Methods Used
* Machine Learning

### Technologies
* Python
* Pandas, jupyter

## Project Description
### Data Preprocessing 
* Perform feature selection and remove unnecessary features
* Use MinMaxScaler to scale the numerical data
* Separate the data into training and testing data
### Building Machine Learning Models
* model_1: SVC model.
  - The score result = 0.841
  - GridSearchCV = best param: {'C': 10, 'gamma': 0.0001} and best score = 0.869  
* model_2, RandomForestClassifier with number of estimators = 200
  - score result = 0.898
  - GirdSearchCV = 0.894
  
The comparison shows RandomForestClassifier model works slightly better than SVC model for this project

## Needs of this project

- data processing/cleaning
- writeup/reporting

## Needs of this project

- data processing/cleaning
- writeup/reporting