# **Comparison of classifier Algorithms on bank marketing Dataset**

Arwa AlBassam & Nouf Alsaeed

**Abstract**


 A bank institution located in Portuguese did a  marketing campaign, where the marketing campaigns is based on phone calls, and sometimes more than one contact to the same client is required, in order to access if the product (bank term deposit) would be (or not) subscribed, using the data provided by the bank we are going to build a classification model  to predict if the client will subscribe a term deposit with a comprehensive analysis with all data cleaning, exploration, visualization, feature selection, model building, and evaluation.



**Design**

This project originates from the Data Science Bootcamp (T5) to Comparison of classifier Algorithms on bank marketing Dataset through the Logistic Regression, K-Nearest Neighbor, Naive Bayes, Decision Tree, SVM, Random forest, Gradient Boosting, Gradient Boosting Machines XGB and Stacking.



**Data**

Using the bank marketing dataset from UCI. The dataset contains 45211 rows and 17 features: age, job, material, education, default, balance, housing, loan, contact, day, month, duration, campaign, pdays, previous, poutcome and y. Where there are Boolean data types and objects.

**Algorithms**

Preprocessing:
* Check if there are any missing values.
* Check if there are any duplicate values.
* Balance Data.
* Feature Scaling.
* Creating Dummy Variables.

Visualization:

* ProfileReport: To present the EDA.
* Barplot: To show the Target for each job.
* Plot: To show the Accuracy and recall for each model.
* countplot: To show the count of target.
* heatmap: To show the Confusion Matrix for each model.
* barplot: To show the Evaluation Metrics for each model.
* plot: To show the ROC Curve.



**Tools**

* Numpy and Pandas for data manipulation.
* Matplotlib and Seaborn for plotting.
* LogisticRegression model from sklearn.linear_model class to build a classification algorithm that is used to predict if the client will subscribe.
* train_test_split function in Sklearn model selection for splitting data.
* KNeighborsClassifier model from sklearn.neighbors to build a classification algorithm that is used to predict if the client will subscribe.
* DecisionTreeClassifier model from sklearn.tree to build a classification algorithm that is used to predict if the client will subscribe.
* RandomForestClassifier model from sklearn.ensemble to build a classification algorithm that is used to predict if the client will subscribe.
* Measure performance of each algorithm using precision_score, recall_score, accuracy_score, roc_auc_score and confusion_matrix from sklearn.metrics module.
* Show the report about the data using ProfileReport from pandas_profiling.
* Jupyter notebook to execute the code.



**Communication**

Presentation.

