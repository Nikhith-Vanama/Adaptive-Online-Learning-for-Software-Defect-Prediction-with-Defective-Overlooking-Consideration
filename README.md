# Adaptive-Online-Learning-for-Software-Defect-Prediction-with-Defective-Overlooking-Consideration

> This project focuses on enhancing software defect prediction using an adaptive online learning framework that continuously learns from incoming software project data.

> Traditional defect prediction models often face challenges like concept drift, imbalanced data, and overlooking defective instances, which leads to poor generalization on real-world evolving projects.

> Our approach introduces an adaptive mechanism that dynamically updates the prediction model while considering defective overlooking — a situation where defective instances are wrongly predicted as non-defective, which is highly critical in software engineering.

> By minimizing defect overlooking and updating models online, the system provides more reliable predictions, helps in early defect detection, and improves software quality assurance in large-scale projects.

# SMOTE (Synthetic Minority Over-sampling Technique) Analysis

> Software defect datasets are usually imbalanced, containing far fewer defective instances compared to non-defective ones. This imbalance can bias machine learning models toward predicting the majority (non-defective) class.

> SMOTE (Synthetic Minority Over-sampling Technique) is applied to balance the dataset by generating synthetic samples of the minority (defective) class. Unlike random oversampling, SMOTE creates new, plausible defect instances by interpolating between existing ones, leading to better generalization.

>  Applying SMOTE ensures the model learns equally from defective and non-defective cases, thus improving recall, F1-score, and reducing the chance of defect overlooking.
