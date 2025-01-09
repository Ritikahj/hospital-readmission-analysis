# Prediction of Diabetes Patient's Hospital Readmission

## Objective
The primary goal of this project is to develop a predictive analytics system to assess the likelihood of 30-day hospital readmissions for diabetic patients. The objectives include:

1. **Identifying Key Predictors**:
   - Analyzing factors like age, medications, and prior hospital visits.
2. **Developing Machine Learning Models**:
   - Building robust models for accurate predictions.
3. **Offering Policy Recommendations**:
   - Suggesting strategies to minimize readmissions and improve care quality.

## Process Overview
The project follows a structured, phased approach:

### 1. Data Preparation
- **Dataset**: Clinical records spanning 10 years of diabetic patient care.
- **Key Steps**:
  - Handling missing data through imputation.
  - Engineering features like patient comorbidities and healthcare utilization.
  - Normalizing continuous variables and balancing class distribution.

### 2. Exploratory Data Analysis (EDA)
- **Insights**:
  - Visualizations and statistics revealed correlations between factors like medications and readmission risk.
  - Significant variables include age, number of medications, and prior hospital visits.

### 3. Machine Learning Models
- **Models Tested**:
  - Logistic Regression, Random Forest, Gradient Boosting, XGBoost, LightGBM, CatBoost.
- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1-score, and ROC-AUC.

### 4. Model Tuning and Selection
- **Optimization**:
  - Hyperparameter tuning using grid search and cross-validation.
- **Best Model**:
  - CatBoost outperformed others with 65% accuracy and the highest ROC-AUC score.

### 5. Feature Importance Analysis
- **Key Features**:
  - Top predictors include:
    - Number of lab procedures (28% importance).
    - Number of medications (24% importance).
    - Age (18% importance).
    - Time in hospital (15% importance).

## Key Findings

### Feature Importance
- Predictors like lab tests, medication count, and hospital stay duration indicate the complexity of patient conditions and their likelihood of readmission.

### Model Performance
- **CatBoost Strengths**:
  - Native handling of categorical features.
  - Resistance to overfitting.
  - Ability to capture non-linear relationships.

### Impact of Predictions
- Achieved a **1.5x improvement** over random predictions.
- Enables hospitals to focus resources on high-risk patients.

## Recommendations

### For Hospitals
- Implement targeted care for high-risk patients identified by the system.
- Enhance post-discharge monitoring for diabetic patients.

### For Policymakers
- Address socio-demographic factors influencing readmissions.
- Promote predictive analytics adoption in healthcare.

## Conclusion
This project successfully developed a predictive analytics system capable of accurately identifying diabetic patients at risk of 30-day readmission. The use of advanced machine learning models, particularly CatBoost, ensures actionable insights for improving patient outcomes and reducing healthcare costs. The results underscore the value of data-driven strategies in tackling critical healthcare challenges.
