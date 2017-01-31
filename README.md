# MakeMyTrip-Contest
Problem:- User clickstream data and information about a group of hotels is provided. • Objective:- Segment users into a given set of classes. The classes are, – Backpackers – Family – Couple • Supervised learning – – Set of training features and target are provided – A test set with features data is provided – Objective:- Predict the target values for the test data

Files:-
1> Report
2> Data files
3> Evaluatipon files
4> SQL queries
5> correlation and ICA plots

Standard
Steps:-
Data extraction:- From csv (transfer data from csv to pandas dataframe in python)
Data mining:- Perform joins to combine data from multiple dataframes into a single dataframe. (join method in pandas)
Data manipulation:- Convert discrete non-numeric data and boolean data to integers. Develop an initial set of features
Break data into test data and training data for test cross-validation
Perform PCA and FA to determine influential features. This step decides the model features.
Choose classifiers –
Try multiple classifiers and determine the F1 score for test cross validation
For each classifier implement GridSearchCV and randomserachCV to obtain an optimum set of parameters
Implement the classifier on the supplied test data and generate the test target csv for submission.Approach:
