# Heart Disease Prediction
## Introduction
Heart disease is one of the leading causes of mortality worldwide, affecting millions of individuals. Early detection of heart disease is essential for preventive treatment and can significantly improve the quality and longevity of patients' lives. Leveraging data and machine learning algorithms to predict heart disease presence can provide additional support for healthcare professionals and enable quicker, more accurate diagnoses.

The Cleveland Heart Disease Dataset, widely used in medical and machine learning research, offers a set of clinical characteristics that can be analyzed to predict the presence of heart disease. This project will utilize this data to train machine learning models to predict a patient’s condition (presence or absence of heart disease) based on given clinical variables.

## Problem Statement
The goal is to predict the presence of heart disease in patients using clinical data. The dataset used in this project is the Cleveland Heart Disease Dataset, available in the UCI Machine Learning Repository. This dataset comprises records from four databases (Cleveland, Hungary, Switzerland, and Long Beach V), but the Cleveland subset is commonly used as a benchmark and is therefore the focus of this project.
The target variable, target, indicates the presence (1) or absence (0) of heart disease in a patient. Our objective is to classify patients as either “diseased” or “healthy” based on variables like age, blood pressure, cholesterol, and more.

## Dataset
The Cleveland Heart Disease Dataset originally contains 76 attributes; however, we will use a subset of 14 attributes, as is standard in published experiments with this dataset. This subset includes relevant demographic and clinical variables, described below:

1. Age: Age of the patient in years.
2. Sex: Gender of the patient (1 = male, 0 = female).
3. CP (Chest Pain Type): Type of chest pain experienced (4 types: typical angina, atypical angina, non-anginal pain, and asymptomatic).
4. Trestbps (Resting Blood Pressure): Resting blood pressure in mm Hg.
5. Chol (Serum Cholesterol): Serum cholesterol level in mg/dl.
6. FBS (Fasting Blood Sugar): Fasting blood sugar > 120 mg/dl (1 = true; 0 = false).
7. Restecg (Resting Electrocardiographic Results): Resting ECG results (0 = normal; 1 = ST-T wave abnormality; 2 = left ventricular hypertrophy).
8. Thalach (Maximum Heart Rate Achieved): Maximum heart rate achieved.
9. Exang (Exercise-Induced Angina): Exercise-induced angina (1 = yes; 0 = no).
10. Oldpeak: ST depression induced by exercise relative to rest.
11. Slope: Slope of the peak exercise ST segment.
12. Ca (Number of Major Vessels Colored by Fluoroscopy): Number of major vessels (0–3) colored by fluoroscopy.
13. Thal: Thalassemia test result (3 = normal; 6 = fixed defect; 7 = reversible defect).
14. Target: The target variable, indicating if heart disease is present (1) or absent (0).

## Evaluation
To assess model performance, the following classification metrics will be used:
-**Confusion Matrix**: Provides a detailed view of true and false predictions for each class.
- **Precision, Recall, and F1 Score**: The F1 Score, which is the harmonic mean of precision and recall, will be the primary performance metric, as it effectively balances precision and recall.

