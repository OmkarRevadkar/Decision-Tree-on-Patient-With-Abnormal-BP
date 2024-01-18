Decision Tree is a supervised learning model. It uses classification algorithm where our target variable is in classes or categories. Sampling is possible and we have performed it on Patient With Abnormal BP Dataset. In this project, we have first tried to build our model on Logistic Regression and then on Decision Tree Classifier. With this, we are able to compare how our model fares on both the algorithms. It is clear that the Decision tree comparitively helps our model perform more better as can also be seen on the AUROC Curve visually.

Following steps are involved:

1. Import the necessary libraries in our Jupyter notebook.
2. Load the dataset.
3. Perform Data Cleaning -- fill missing values, standardization, normalization, etc.
4. Random Sampling by splitting data into train and test data.
5. Build the model with Decision Tree Classifier on train (fit on train).
6. Predict on test data.
7. Build the confusion matrix to be able to evaluate/judge the performance of our model.
8. Evaluate the model using various parameters like accuracy, recall, precision and f1 ratio along with the AUROC Curve.
