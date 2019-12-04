# 15-688 Practical Data Science Project

In this project, we extract yellow taxi data from NYC Open Data, conduct data preprocessing, data analysis, feature engineering and implement a series of models to predict taxi trip duration. Based on our experiments, we obtain the following conclusions:

Linear regression and its variations are treated as our baseline model. On both train set and test set, they get higher RMSE score. Among simple Linear Regression, Ridge, Lasso and Elastic Net, Ridge regression has slightly better performance over the test set.

Compared with Linear Regression model, Random Forest model has around 15% lower RMSE both on train set and test set.

Performance of Gradient Boost model is worse than random forest which may cause from the inappropriate selection of some hyper-parameters.

Xgboost model achieves lowest RMSE score on train set and test set. It is an optimized distributed Gradient Boosting method which leads to both greater metrics performance and less time cost.

During the whole project, we experience the full data science development cycle. We notice the importance of data exploration and data cleaning before building models. And after understanding data distribution and building baseline, we furthermore improve our feature selection based on the baseline results until we get the optimal features. Finally, we utilize optimal feature space to construct model and achieve the best result. For future work, we will go deeper with the algorithm in each model and try to apply them in different aspects.
