Step 1: Collect Data X = features (inputs) y = target (continuous value you want to predict) Example: ai_impact_student_performance_dataset

Step 2: Split Data Divided data into: Training set (to train the model) testing set (to check performance)

step 3: Create the Model Use a Decision Tree Regressor: from sklearn.tree import DecisionTreeClassifier model = DecisionTreeClassifier()

Step 4: Train the Model Teach the Model using training data: model.fit(X_train, y_train)

Step 5: Make Predictions Use the trained model to predict new values: y_pred = model.predict(X_test)

Step 6: Confusion Matrix : [[ 41   0  36]
 [  0 204  64]
 [ 23  71 361]]
Accuracy Score : 0.7575
Accuracy in Percentage : 75 %


