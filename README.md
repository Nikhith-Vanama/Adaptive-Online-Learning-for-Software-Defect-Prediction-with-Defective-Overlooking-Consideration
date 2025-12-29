# Adaptive-Online-Learning-for-Software-Defect-Prediction-with-Defective-Overlooking-Consideration

> This project focuses on enhancing software defect prediction using an adaptive online learning framework that continuously learns from incoming software project data.

> Traditional defect prediction models often face challenges like concept drift, imbalanced data, and overlooking defective instances, which leads to poor generalization on real-world evolving projects.

> Our approach introduces an adaptive mechanism that dynamically updates the prediction model while considering defective overlooking — a situation where defective instances are wrongly predicted as non-defective, which is highly critical in software engineering.

> By minimizing defect overlooking and updating models online, the system provides more reliable predictions, helps in early defect detection, and improves software quality assurance in large-scale projects.

# SMOTE (Synthetic Minority Over-sampling Technique) Analysis

> Software defect datasets are usually imbalanced, containing far fewer defective instances compared to non-defective ones. This imbalance can bias machine learning models toward predicting the majority (non-defective) class.

> SMOTE (Synthetic Minority Over-sampling Technique) is applied to balance the dataset by generating synthetic samples of the minority (defective) class. Unlike random oversampling, SMOTE creates new, plausible defect instances by interpolating between existing ones, leading to better generalization.

>  Applying SMOTE ensures the model learns equally from defective and non-defective cases, thus improving recall, F1-score, and reducing the chance of defect overlooking.

# Random Forest Classifier

> Random Forest is an ensemble learning method that builds multiple decision trees during training.

> It combines the predictions of all trees (majority voting) to improve accuracy and reduce overfitting.

> It works by randomly selecting features and samples to create diverse trees, ensuring strong generalization.

# Logistic Regression

> Logistic Regression is a classification algorithm that models the probability of an outcome using a sigmoid function.

> It finds the best-fit decision boundary by optimizing weights using maximum likelihood estimation.

> It works well for binary and multi-class classification with linearly separable datasets.

# Decision Tree Classifier

> A Decision Tree splits data into branches based on feature values, forming a tree-like structure.

> Each split is chosen using metrics like Gini impurity or entropy to maximize information gain.

> It makes decisions by traversing from the root node to a leaf node representing the predicted class.

# Support Vector Machine (SVM)

> SVM aims to find the optimal hyperplane that maximally separates different classes.

> It uses support vectors (critical data points) to define the decision boundary.

> With kernel functions, SVM can handle both linear and non-linear classification problems effectively.

# Gaussian Naive Bayes (GaussianNB)

> GaussianNB applies Bayes’ theorem with the assumption that features follow a Gaussian (normal) distribution.

> It calculates class probabilities based on feature likelihoods and prior probabilities.

> It is highly efficient and works well for high-dimensional, probabilistic classification tasks.

# XGBoost Classifier (XGBClassifier)

XGBoost is an optimized gradient boosting algorithm that builds trees sequentially to correct previous errors.

It uses regularization, parallel processing, and efficient tree pruning to improve accuracy and speed.

It works by minimizing a loss function using gradient descent, making it powerful for structured/tabular data.
