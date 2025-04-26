This project is designed to predict health outcomes (specifically Blood Pressure and Churn related to diabetic patients) using various machine learning techniques. It follows a full Data Science Lifecycle, including:

📊 Key Steps:
Data Loading and Exploration:

The dataset (Healthcare-Diabetes.csv) is loaded.

Initial data types and statistical summaries are generated.

Data Preprocessing:

Handling Missing Values: Missing values are filled or dropped.

Removing Outliers: Outliers are detected and removed using the IQR method.

Feature Scaling: Data is normalized using StandardScaler and MinMaxScaler.

Handling Categorical Variables: Encoding is applied to columns like ContractRenewal and DataPlan.

Feature Selection:

Random Forest Feature Importance.

Chi-Square Test with SelectKBest.

Mutual Information (Info Gain) Scores.

Data Visualization:

Histograms, Boxplots, Correlation Heatmaps, and Pairplots for feature relationships and outlier detection.

Churn count plots to understand the target distribution.

Model Building:

Linear Regression to predict Monthly Charges.

Classification Models (to predict Churn):

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Model Evaluation:

Performance metrics like Accuracy, Confusion Matrix, and Classification Reports are generated.

Visualization of Actual vs Predicted values in regression tasks.

🛠️ Technologies & Libraries Used:
Python (pandas, numpy, matplotlib, seaborn, sklearn)

Scikit-learn for modeling and preprocessing.

🎯 Final Outcome:
Prediction of Blood Pressure using regression.

Prediction of Churn (likely dropout from healthcare program) using classification models.

Insightful visualization for understanding the data and feature importance.
