# Decision Tree
A Decision Tree is a supervised machine learning algorithm used for classification and regression tasks. It models decisions and their possible consequences as a tree-like structure, where:

- Each internal node represents a test or decision on a feature.

- Each branch represents the outcome of the test.

- Each leaf node represents a class label (for classification) or a continuous value (for regression).

# Decision Tree Project

## Overview
This project demonstrates the implementation and use of Decision Tree algorithms for classification and regression tasks. Decision Trees are intuitive and easy-to-interpret models that split data based on feature values to predict outcomes.

## Features
- Supports classification and regression
- Visualizes decision tree structure
- Handles both numerical and categorical features
- Includes pruning to reduce overfitting

## How It Works
- The dataset is split recursively based on the feature that provides the best information gain (or another splitting criterion).
- Splitting continues until stopping criteria are met (e.g., maximum depth or minimum samples per leaf).
- The final prediction is made based on the leaf nodes.

## Usage
1. Prepare your dataset in a CSV format with features and target labels.
2. Load the dataset into the script.
3. Train the Decision Tree model.
4. Use the trained model to predict on new data.
5. Visualize or export the tree if needed.
