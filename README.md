# Heart Disease Prediction Project

## Overview
This project predicts the likelihood of heart disease using Logistic Regression, Naive Bayes, and K-Nearest Neighbors (KNN) classifiers. The goal is to compare the models and choose the most accurate one for identifying individuals at risk.

---

## Dataset
The dataset contains health-related data such as cholesterol levels, blood pressure, age, and other medical indicators. The target column (`target`) indicates whether heart disease is present (`1`) or absent (`0`).

### Features:
- `age`: Age of the patient.
- `sex`: Gender (1 = male; 0 = female).
- `cp`: Chest pain type.
- `trestbps`: Resting blood pressure (mm Hg).
- `chol`: Serum cholesterol (mg/dl).
- `fbs`: Fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false).
- `restecg`: Resting electrocardiographic results.
- `thalach`: Maximum heart rate achieved.
- `exang`: Exercise-induced angina (1 = yes; 0 = no).
- `oldpeak`: ST depression induced by exercise relative to rest.
- `slope`: Slope of the peak exercise ST segment.
- `ca`: Number of major vessels (0-3) colored by fluoroscopy.
- `thal`: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect).
- `target`: 1 = Disease; 0 = No Disease.

---

## Setup Instructions
1. Clone the repository: `git clone <repository-url>`.
2. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn joblib
