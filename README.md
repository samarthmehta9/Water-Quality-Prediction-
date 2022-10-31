# Water-Quality-Prediction-
ML Based water quality prediction using supervised machine learning algorithms
This project predicts the potability of water by using supervised ML algorithms like:
1. Logistic Regression
2. DecisionTreeClassifier
3. RandomForestClassifier
4. SVM
5. Gaussian Naive Bayes
6. Multinomial Naïve Bayes
7. K-Nearest Neighbors
8. XGBoost
9. Artificial Neural Network


## Approach:
1.Pre-processing the Data
2.Generating New Samples
3.Scaling Data
4.Splitting Data
5.Hyperparameter Tuning
6.ANN


## Results Before Hyperparameter Tuning

Model | Testing Score %| Training Sore %
| :--- | ---: | :---:
Logistic Regression  | 52.3 | 49.4
Random Forest Classifier  | 99.99 | 67.9
Decision Tree Classifier  | 99.99 | 60.8
SVC  | 52.3 | 49.4
Gaussian NB  | 56.6 | 54.8
MultinomialNB  | 50.4 | 50.9
K Nearest 
Neighbours 
Classifier  | 74.9 | 58.6
XGBoost 
Classifier  | 76.7 | 59.18


## Results After Hyperparameter Tuning

Model | Parameters | Training Sore %
| :--- | ---: | :---:
Logistic Regression  | ‘penalty’, ‘C’  | 51.98
Random Forest Classifier  | 'n_estimators’, 
‘max_features’, 
‘max_depth’  | 67.27
Decision Tree Classifier  | ‘max_features’, 
‘max_depth’, 
‘criterion’
 | 57.90
SVC  | ’C’, ‘gamma’, 
‘kernel’| 68.79
Gaussian NB  | ‘var_smoothing’  | 55.30
MultinomialNB  | ‘alpha’  | 49.91
K Nearest 
Neighbours 
Classifier  | ’n_neighbours’, 
‘weights’, 
‘metric’. | 60.96
XGBoost 
Classifier  | ‘learning_feature
s’, 
’max_features’, 
‘max_depth’, 
‘n_estimators’. | 68.31
