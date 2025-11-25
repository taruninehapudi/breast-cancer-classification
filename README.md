# breast-cancer-classification
Project Overview

• Machine learning project to classify tumors as malignant or benign
• Uses the Breast Cancer Wisconsin dataset
• Includes EDA, feature analysis, and predictive modeling

Objectives

• Understand feature patterns of malignant vs benign tumors
• Visualize correlations and distributions
• Build ML models for classification
• Evaluate accuracy and performance metrics
• Identify most important medical indicators

Tools Used

• Python
• Pandas
• NumPy
• Matplotlib
• Seaborn
• Scikit-learn
• Jupyter Notebook

Files in This Repository

• breast_cancer_classification.ipynb — Main notebook
• sample_breast_cancer.csv — Sample dataset
• README.md — Documentation

Dataset Source

• Breast Cancer Wisconsin dataset (Kaggle)

Important Note (Path Adjustment Required)

• The notebook originally loads the dataset from a local path
• Users must replace it with their own dataset location
• Or use the provided sample_breast_cancer.csv file

Key Insights

• Malignant tumors show higher radius, perimeter, and concavity
• Clear visual separation between malignant and benign samples
• Strong correlations between radius, area, and compactness
• Feature importance highlights medically relevant predictors

Modeling Summary

• Logistic Regression, Random Forest, and SVM models evaluated
• High overall accuracy across models
• Random Forest performed best
• Confusion matrix confirms strong classification ability

Clinical Recommendations

• Use model as a supporting diagnostic aid
• Prioritize high-risk feature combinations for further testing
• Combine model with additional patient data for higher accuracy
• Encourage early screening supported by insights

How to Run

• Download repository
• Place sample dataset in same folder as the notebook
• Open the notebook in Jupyter
• Adjust dataset path if required
• Run all cells sequentially
