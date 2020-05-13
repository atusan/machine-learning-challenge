# machine-learning-challenge

model_1, I used SVC model the results for training and testing data are:
Training Data Score: 0.845
Testing Data Score: 0.841

GridSearchCV for this model using
 param_grid = {'C': [1, 5, 10],
              'gamma': [0.0001, 0.001, 0.01]}
Results are:
best param: {'C': 10, 'gamma': 0.0001}
best score: 0.869

model_2, I used RandomForestClassifier with number of estimators=200 