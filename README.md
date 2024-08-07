This repository contains a machine learning model designed to detect diabetes using clinical data. The project was developed as part of a hackathon, focusing on building a robust and accurate classification system leveraging the power of Random Forest.

Key Features
Random Forest Classifier: Utilized for its robustness and high performance in classification tasks.
Data Preprocessing: Includes feature scaling and handling class imbalance using SMOTE.
Exploratory Data Analysis: Provides insights through visualizations such as histograms, box plots, and heatmaps.
Cross-validation: Ensures model generalizability and robustness across different data splits.
Dataset
The model is trained on a dataset containing clinical features relevant to diabetes detection. The dataset is included in the repository as DD.csv and contains the following columns:

Pregnancies: Number of pregnancies.
Glucose: Plasma glucose concentration.
BloodPressure: Diastolic blood pressure.
SkinThickness: Triceps skin fold thickness.
Insulin: 2-Hour serum insulin.
BMI: Body mass index.
DiabetesPedigreeFunction: Diabetes pedigree function.
Age: Age of the patient.
Outcome: 1 if the patient has diabetes, 0 otherwise.
Dataset Summary
Number of Records: 768
Number of Features: 8
Target Variable: Outcome (binary classification)
