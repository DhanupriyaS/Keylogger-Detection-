# Keylogger Detection Using Machine Learning
Keylogger Detection Using Machine Learning
Keyloggers pose significant cybersecurity risks, capturing keystrokes to steal sensitive data such as passwords, personal information, and financial details. This project uses machine learning to identify and classify keylogger activity by analyzing network behavior patterns, aiming to provide an efficient and automated solution to detect these threats.

Objectives
Detect keylogger activity by analyzing network behavior data.
Achieve high accuracy in classifying keylogger versus non-keylogger activity.
Lay the groundwork for future development in real-time keylogger detection systems.

Methodology
Dataset
The dataset is based on network behavior characteristics and includes features that help differentiate normal activity from keylogger activity.
https://www.kaggle.com/datasets/subhajournal/keylogger-detection

Machine Learning Models
Random Forest: Achieved the highest accuracy of 98%.
XGBoost: Achieved 95% accuracy, performing robustly in handling complex relationships.
Logistic Regression: Achieved a baseline accuracy of 59%, providing a comparative benchmark.
Features
Supervised learning models with clear metrics evaluation (accuracy, precision, recall, and F1-score).
Data preprocessing and exploratory analysis for feature engineering and understanding.
Network behavior dataset tailored for keylogger detection tasks.

Results
Random Forest: 98% accuracy, demonstrating superior performance in classification tasks.
XGBoost: 95% accuracy, effective in handling feature relationships.
Logistic Regression: 59% accuracy, serving as a baseline model.
Visualizations of confusion matrices and detailed performance metrics.

Future Enhancements
Further optimize feature engineering to enhance model accuracy.
Implement hyperparameter tuning for even better performance.
Explore real-time detection implementation for practical applications.
Incorporate additional datasets to ensure model robustness.
