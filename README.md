# machine-learning-challenge
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
To help process this data,I tired two different 
model_1, I used SVC model the results for training and testing data are:
Training Data Score: 0.845
Testing Data Score: 0.841

GridSearchCV for this model using
 param_grid = {'C': [1, 5, 10],
              'gamma': [0.0001, 0.001, 0.01]}
Results are:
best param: {'C': 10, 'gamma': 0.0001}
best score: 0.869

model_2, I used RandomForestClassifier with number of 
estimators = 200 and 
result = 0.898 that shows it works slightly better than previous model

GirdSearchCV for this model = 0.894