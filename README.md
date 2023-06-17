# Ml-From-Scratch 
The code defines a DecisionTree class that represents a decision tree model.
The fit method is used to train the decision tree on a given dataset (X features and y labels).
The predict method takes a set of features (X) and returns the predicted labels based on the trained decision tree.
The decision tree is grown recursively using the _grow_tree method, which uses information gain to determine the best splitting criteria.
The _best_criteria method finds the best feature and threshold to split the data at each node.
The _information_gain method calculates the information gain at a node based on the given splitting criteria.
The _split method splits the data into left and right subsets based on the selected feature and threshold.
The _traverse_tree method traverses the decision tree to predict the label for a given feature vector.
The _most_common_label method returns the most common label in a given set of labels.
The code also includes an example usage of the decision tree classifier on the breast cancer dataset from scikit-learn.
K-Nearest Neighbors (KNN) Classifier:

The code defines a KNN class that represents a KNN classifier.
The fit method is used to train the classifier on a given dataset (X features and y labels).
The predict method takes a set of features (X) and returns the predicted labels based on the trained KNN model.
The _predict method predicts the label for a single data point by finding the k nearest neighbors and using majority voting.
The code includes an example usage of the KNN classifier on the Iris dataset from scikit-learn.
