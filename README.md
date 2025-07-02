# Maternal_health_risk_prediction
Project Overview
This project focuses on classifying maternal health risks using machine learning techniques based on clinical parameters. By analyzing various health indicators, the goal is to predict whether a pregnant woman falls into a low, mid, or high-risk category. Accurate classification can assist healthcare professionals in making timely and informed decisions for patient care.

Dataset
Source: Maternal Health Risk Data Set
Features Include:

Age

Systolic Blood Pressure

Diastolic Blood Pressure

Blood Oxygen Level

Body Temperature

Heart Rate

Risk Level (Target)

Exploratory Data Analysis (EDA)
Key visualizations were created to better understand the data:

Count plot for risk level distribution

KDE plot for body temperature

Histograms to show age distribution

Scatter plots for blood pressure relationships

Boxplots to detect outliers

Correlation heatmap to identify linear relationships

These visualizations helped in feature understanding and informed model design.

Models Implemented
1. Decision Tree Classifier
A simple, interpretable model

Accuracy Achieved: 82%

2. Random Forest Classifier
An ensemble model combining multiple decision trees

Accuracy Achieved: 84%

Both models were trained using a 70-30 train-test split. Accuracy, confusion matrices, and classification reports were used to evaluate performance.

Performance Comparison
Model	Accuracy
Decision Tree	82%
Random Forest	84%

Random Forest slightly outperformed the Decision Tree model due to its ability to reduce overfitting and leverage multiple learners for better generalization.

Additional Work
Dataset was stored in an SQLite database to enable future querying and analysis as part of a data pipeline.

Conclusion
Both models performed well, with Random Forest achieving the highest accuracy of 84%. This project demonstrates that machine learning can be effectively used for health risk prediction and could potentially be developed further into clinical decision support tools.
