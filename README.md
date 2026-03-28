# Sales-Data-Analysis
Sales Data Analysis - Classification Project
Project Overview Target variable: Payment Method (Gift Card / Credit Card).

Goal: Transaction details (Product, Price, Quantity, Manager, City)

Dataset Details File Name:  Sales-Data-Analysis.csv
Columns:
Order ID
Date
Product
Price
Quantity
Payment Method (Target)
Manager
City                                                                                                      

Workflow Steps
Import Libraries → pandas, scikit-learn, seaborn, matplotlib
Load Dataset → pd.read_csv()
Explore Data → df.head(), df.columns
Feature Selection → Product, Price, Quantity, Manager, City
Target Selection → Payment Method
Encoding → LabelEncoder for categorical variables
Train-Test Split → 80% training, 20% testing
Model Training → RandomForestClassifier
Evaluation → Accuracy, Classification Report, Confusion Matrix
            
Results
Accuracy: Printed using accuracy_score()
Classification Report: Precision, Recall, F1-score
Confusion Matrix: Visualized with seaborn heatmap

Future Improvements
Add regression model for predicting sales amount.
Try other classifiers (Logistic Regression, SVM, XGBoost).
Perform feature engineering (e.g., time-based features).
Hyperparameter tuning for better accuracy.

Requirements -Python 3.11+ -Libraries: pandas, scikit-lea
