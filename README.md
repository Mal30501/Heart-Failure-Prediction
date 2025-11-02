# Heart Failure Prediction Model

This project applies supervised machine learning to predict the likelihood of patient mortality caused by heart failure.  
Using structured clinical data, the model analyzes multiple physiological and lifestyle factors to identify patterns associated with high-risk patients.  
Early detection through predictive modeling can support timely medical intervention and improve healthcare decision-making.

---

## Overview
Cardiovascular diseases are the leading cause of death globally, accounting for nearly 18 million deaths each year.  
This project focuses on building a predictive system that classifies patients based on the probability of death due to heart failure, helping hospitals and practitioners take proactive steps in treatment and monitoring.

---

## Dataset
The dataset is included in this repository for easy reproducibility.  
It contains structured clinical data with 12 independent features and one binary target variable.

**Features include:**  
- `age`, `anaemia`, `creatinine_phosphokinase`, `diabetes`, `ejection_fraction`,  
  `high_blood_pressure`, `platelets`, `serum_creatinine`, `serum_sodium`, `sex`,  
  `smoking`, `time`  
- **Target:** `DEATH_EVENT` (Binary classification: 1 = death occurred, 0 = survived)

---

## Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Techniques:** Logistic Regression, Data Preprocessing, Correlation Analysis, Model Evaluation

---

## Workflow
1. **Data Preprocessing**  
   - Handled missing values and normalized numeric features.  
   - Encoded categorical variables and performed exploratory data analysis (EDA).

2. **Feature Analysis**  
   - Identified top contributing features such as serum creatinine, ejection fraction, and age.  
   - Visualized relationships using Seaborn heatmaps and pairplots.

3. **Model Training**  
   - Trained a **Logistic Regression** classifier using Scikit-learn.  
   - Optimized hyperparameters for model generalization.

4. **Model Evaluation**  
   - Evaluated performance using confusion matrix, precision, recall, F1-score, and accuracy.  
   - Compared results against baseline metrics.

---

## Results
- **Model:** Logistic Regression  
- **Accuracy:** ~84%  
- **Precision:** 82%  
- **Recall:** 85%  
- **F1 Score:** 83%  

The model effectively classifies high-risk patients, offering a reliable foundation for clinical decision support.

---
