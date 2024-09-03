# Breast Cancer Detection using different Machine Learning algorithms and a simple neural network

# Exploratory Data Analysis Results
- No missing Values
- All are continuous numerical values except for Target column
- Mean is slightly more than the median for most of the features. So it is right skewed.
- Slight imbalance in the dataset (Benign(0) cases are more than Malignant(1) cases
- Mean of most features are clearly larger for Malignant cases compared to the benign cases (Groupby)

# Accuracy of different machine learning algorithms
- LogisticRegression: 0.9210526315789473
- Decision Tree:  0.9298245614035088
- Random Forrest: 0.9385964912280702
- MLPClassifier: 0.868421052631579
- GridSearchCV and RandomForestClassifier (hyperparameters tuning): 0.956140350877193
- combining different models (RandomForestClassifier, LogisticRegression, SVC) : 0.9385964912280702

# Built a predictive system on the algorithm with highest accuracy

# Built a neural network to detect cancer
- Epoch 1/10: 13/13 ━━━━━━━━━━━━━━━━━━━━ 1s 19ms/step - accuracy: 0.7369 - loss: 0.5559 - val_accuracy: 0.8696 - val_loss: 0.4203
- Epoch 10/10: 13/13 ━━━━━━━━━━━━━━━━━━━━ 0s 6ms/step - accuracy: 0.9613 - loss: 0.1210 - val_accuracy: 0.9783 - val_loss: 0.1099
- Plotted the model accuracy and the model loss curve
- Accuracy of model on test data: 0.9385964870452881

# Built a predictive system on the algorithm with highest accuracy
