# Alzheimer's Disease Risk Factors — Capstone Project

## Overview

This capstone project explores potential risk factors associated with Alzheimer’s disease using a dataset of 2,149 patients from Kaggle. The dataset includes demographic, lifestyle, clinical, and cognitive data. The analysis aims to uncover trends related to diagnosis, highlight meaningful indicators, and evaluate the potential for basic predictive modeling.

The project was completed in Google Colab and includes structured steps: data preparation, exploratory analysis, diagnosis comparison, statistical testing, and model development.

---

## Dataset Summary

- **Source:** [Alzheimer’s Disease Dataset on Kaggle](https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset)
- **Format:** CSV
- **Records:** 2,149 patients
- **Features:** 35 columns including:
  - Demographics: Age, Gender, Ethnicity, Education Level
  - Lifestyle: Physical Activity, Sleep Quality, Alcohol Use, Smoking, Diet
  - Medical History: Diabetes, Depression, Hypertension, Head Injury
  - Cognitive Metrics: MMSE, Confusion, Forgetfulness, Functional Assessment
- **Target Column:** `Diagnosis` (0 = Not Diagnosed, 1 = Diagnosed)

---

## Project Steps

1. **Data Cleaning**  
   - Removed duplicates and non-informative columns  
   - Mapped encoded values to readable categories  

2. **Exploratory Data Analysis**  
   - Histograms, box plots, and correlation heatmaps  
   - Summary statistics of lifestyle, clinical, and cognitive features  

3. **Diagnosis-Based Analysis**  
   - Grouped means and bar charts comparing diagnosed vs. non-diagnosed patients  
   - Highlighted significant symptom and lifestyle differences  

4. **Focused Assessment: MMSE Score**  
   - Boxplot and statistics comparing MMSE cognitive scores by diagnosis  

5. **Chi-Square Testing**  
   - Tested for statistical dependence between diagnosis and categorical variables (Gender, Ethnicity, Education Level)  

6. **Logistic Regression Modeling**  
   - Trained a basic predictive model using selected features  
   - Reported accuracy, confusion matrix, and feature importance  

7. **Conclusion**  
   - Summarized cognitive and lifestyle trends  
   - Identified opportunities for future research and model refinement  

---

## How to Run the Notebook

1. Open the `.ipynb` notebook in [Google Colab](https://colab.research.google.com/)
2. Upload the dataset file (`alzheimers_disease_data.csv`)
3. Run all cells in order to reproduce the analysis and visualizations

---

## Author

**Kayden Rumsey**  
Kayden.Rumsey@gmail.com  
