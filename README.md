# ClassificationProblem
The objective of this assessment is to evaluate your understanding and ability to apply supervised learning techniques to a real-world dataset.

# Dataset:
Use the breast cancer dataset available in the sklearn library.

Implement the following five classification algorithms:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Machine (SVM)
5. k-Nearest Neighbors (k-NN)
   
1. Logistic Regression is a linear model that predicts the probability of a class (e.g., malignant vs. benign). It uses the sigmoid function to output probabilities between 0 and 1.It works well for binary classification problems like this one.Provides interpretable results in terms of feature importance.Performs well if the data is linearly separable.

2. Decision Tree Classifier splits data based on feature values using if-else conditions to create a tree structure. It continues splitting until a stopping criterion is met (e.g., max depth). It handles both linear and non-linear relationships well.Easy to interpret and visualize.Works well even with minimal preprocessing (no need for feature scaling).

3. Random Forest Classifier consists of multiple decision trees (ensemble learning). Each tree is trained on a different subset of data, and the final prediction is made using majority voting.It reduces overfitting compared to a single decision tree.Provides high accuracy and robustness.Handles missing data and outliers well.

4. Support Vector Machine (SVM) finds the optimal hyperplane that maximizes the margin between two classes. It can use different kernel functions (linear, polynomial, RBF) to handle complex relationships.It works well with high-dimensional data (many features).Effective when the dataset is not too large.Robust against overfitting, especially with proper tuning.

5. k-Nearest Neighbors (k-NN) is a distance-based algorithm that classifies a data point based on the majority class of its nearest neighbors.It is simple and intuitive.Can handle non-linear relationships well.Works well with balanced datasets but can be slow with large datasets.

# Model Comparison
Compare the performance of the five classification algorithms.
Which algorithm performed the best and which one performed the worst?
