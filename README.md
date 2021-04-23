# ML-algorithm-tests

What does this code ? 😀

This code takes the data_set and splits it as training and test according to the input parameter(4th). Then according to the request's type(regression or classification) function tests the listed algorithms and outputs the their accuracy results with using different metrics.

!Function inputs=(problem_type,data_set,target_attribute,test_percentage)
*  First Parameter will be use to determine is that regression or classification problem.
*  Second Parameter will be our taken data as .csv file
*  Third Parameter will be the target feature.
*  Fourth Parameter will be the proportion of test data.


Used Regression Algorithms:

 * ("LGBM", LGBMRegressor()),
 * ("XGBR", XGBRegressor()),
 * ("GBR", GradientBoostingRegressor()),
 * ("RFR", RandomForestRegressor(random_state = 42)),
 * ("DT", DecisionTreeRegressor(max_leaf_nodes = 10)),
 * ("MLP", MLPRegressor()),
 * ("Knn", KNeighborsRegressor()),
 * ("SVR", SVR("linear")),

Used Classification Algorithms:

* ("LR", LogisticRegression(max_iter=10000,solver = "liblinear")),
* ("LDA", LinearDiscriminantAnalysis()),
* ("KNN", KNeighborsClassifier()),
* ("DT", DecisionTreeClassifier()),
* ("NB", GaussianNB()),
* ("SVM", SVC()),
* ("RF", RandomForestClassifier(max_features = 8, 
                          min_samples_split = 5, 
                          n_estimators = 500)),



!Entered data sets used for test the function. 

