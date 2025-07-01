# ML-Task-6
This project applies the K-Nearest Neighbors (KNN) algorithm to classify species of iris flowers based on four morphological measurements:
Sepal length
Sepal width
Petal length
Petal width

The dataset used is the well-known Iris dataset, containing 150 samples across three classes:
Setosa
Versicolor
Virginica
Steps Performed:
Dataset Reading

Read the Iris dataset.

Feature Normalization

Applied StandardScaler to normalize all four features.

This step ensures that no feature dominates distance calculations due to differing scales.

Train-Test Split

Split the dataset into 70% training and 30% testing (105 train samples, 45 test samples).

Used stratify=y to maintain class balance in the test set (15 samples per class).

Model Training and Evaluation

Trained KNN classifiers with different values of K (1, 3, 5, and 7).

For each K:

Fit the model on the training data.

Predicted labels for the test set.

Computed accuracy and plotted the confusion matrix to evaluate performance.

Results and Observations:
KNN achieved high classification accuracy, with only 1 misclassification in the test set when using K=7.

Confusion Matrix Insights:

All Setosa and Versicolor samples were correctly classified.

One Virginica sample was misclassified as Versicolo


