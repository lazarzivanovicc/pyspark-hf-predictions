# Heart Failure Prediction using PySpark

This project focuses on solving Heart Failure prediction using PySpark and the [Heart Failure Prediction - Clinical Records dataset](https://www.kaggle.com/datasets) from Kaggle.

## Dataset Description

The dataset contains medical records of 5000 patients who experienced heart failure, collected during their follow-up period. Each patient profile includes 13 clinical features:

- **age**: Age of the patient (years)
- **anaemia**: Decrease of red blood cells or hemoglobin (boolean)
- **creatinine phosphokinase (CPK)**: Level of the CPK enzyme in the blood (mcg/L)
- **diabetes**: If the patient has diabetes (boolean)
- **ejection fraction**: Percentage of blood leaving the heart at each contraction (percentage)
- **high blood pressure**: If the patient has hypertension (boolean)
- **platelets**: Platelets in the blood (kiloplatelets/mL)
- **sex**: Woman or man (binary)
- **serum creatinine**: Level of serum creatinine in the blood (mg/dL)
- **serum sodium**: Level of serum sodium in the blood (mEq/L)
- **smoking**: If the patient smokes or not (boolean)
- **time**: Follow-up period (days)
- **[TARGET] DEATH_EVENT**: If the patient died during the follow-up period (boolean)

## Objective

The primary goal of this project is to develop a model that predicts the survival of a patient with heart failure. Given that this is a binary classification problem, we will implement the XGBoost Classifier.

