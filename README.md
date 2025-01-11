## Day-64-Day-65---Decision-Trees-Random-Forests-and-SVM
As part of a 75-day data analysis challenge, this work on Python covers Decision Trees, Random Forests, and SVMs.

### 1. Decision Trees

A Decision Tree is a flowchart-like structure used for both classification and regression tasks. It splits the data into subsets based on feature values, creating a tree where each internal node represents a decision on a feature, each branch represents the outcome of the decision, and each leaf represents a final prediction (class or value).

**Key Characteristics:**

Easy to interpret and visualize.

Can handle both numerical and categorical data.

Prone to overfitting if not pruned or regularized.

### 2. Random Forests

A Random Forest is an ensemble learning method that combines multiple decision trees to improve prediction accuracy and reduce overfitting. Each tree in the forest is trained on a random subset of the data (bootstrap sampling), and predictions are aggregated (via majority voting for classification or averaging for regression).

**Key Characteristics:**

Handles large datasets well.

Less prone to overfitting than a single decision tree.

Robust to noise and works well with missing data.

### 3. Support Vector Machines (SVMs)

A Support Vector Machine is a supervised learning algorithm used for classification and regression tasks. It aims to find the hyperplane that best separates classes in the feature space while maximizing the margin (distance between the hyperplane and the nearest data points from each class).

**Key Characteristics:**

Effective in high-dimensional spaces.

Can use different kernel functions (linear, polynomial, RBF) to handle non-linear relationships.

Sensitive to parameter tuning (e.g., C, gamma).
