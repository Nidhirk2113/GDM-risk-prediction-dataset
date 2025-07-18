# 🎯 GDM Risk Prediction Dataset

## 🧬 Overview

This dataset supports the development of machine learning models for predicting **Gestational Diabetes Mellitus (GDM)** — a pregnancy-related condition with serious health implications for both mother and child. It comprises over **7,000 anonymized records**, each labeled as GDM-positive or non-GDM, suitable for a wide range of **supervised learning tasks**.

What sets this dataset apart is its hybrid nature — it includes both **clinical features** (e.g., Age, BMI, Glucose) and **genomic markers** (e.g., gene expression levels, SNPs), enabling biologically informed risk prediction models.

---

## 📂 Dataset Files

| Filename              | Description                                  |
|-----------------------|----------------------------------------------|
| `gdm_oversampled.csv` | Oversampled version with balanced class ratio |
| `gdm_downsampled.csv` | Downsampled version for model testing         |
| `README.md`           | This documentation                           |

---

## 🧾 Dataset Format

- **Format:** CSV (Comma-Separated Values)  
- **Encoding:** UTF-8  
- **Total Records:** 7,000+  
- **Target Column:** `GDM`  
  - `1` → GDM-positive  
  - `0` → GDM-negative

---

## 📊 Feature Summary

| Feature Name              | Description                                              |
|---------------------------|----------------------------------------------------------|
| `Age`                     | Age of the patient (years)                               |
| `Pregnancies`             | Number of prior pregnancies                              |
| `Glucose`                 | Plasma glucose concentration (mg/dL)                     |
| `BloodPressure`           | Diastolic blood pressure (mm Hg)                         |
| `SkinThickness`           | Triceps skinfold thickness (mm)                          |
| `Insulin`                 | Serum insulin level (μU/mL)                              |
| `BMI`                     | Body Mass Index (kg/m²)                                  |
| `DiabetesPedigreeFunction`| Diabetes risk based on family history                   |
| `FPG`                     | Fasting Plasma Glucose (mg/dL)                           |
| `GeneA_Expression`        | Normalized expression of Gene A                          |
| `GeneB_Expression`        | Normalized expression of Gene B                          |
| `SNP1` to `SNP4`          | Normalized/encoded Single Nucleotide Polymorphisms       |
| `GDM`                     | 🎯 Target variable (1 = GDM, 0 = Non-GDM)                 |

> 💡 *Note: All gene expression and SNP features have been appropriately normalized and encoded.*

---

## 🧠 Potential Use Cases

- 🔍 **Predictive Modeling** (ML/DL classifiers)
- 🧪 **Biomarker Discovery** (Gene/SNP impact analysis)
- 🧰 **Feature Selection** (e.g., PSO, SHAP, LIME)
- 💻 **Clinical Decision Support Systems**

---

## 📈 Model Evaluation Tips

- Apply **normalization/standardization** to numeric features
- Use **stratified cross-validation** for fair model assessment
- Suggested evaluation metrics: **Precision, Recall, F1-Score, AUC**
- Test hybrid models combining both clinical + genomic features

---

## 🤖 Suggested Algorithms

- **Traditional ML**: Logistic Regression, Decision Trees, Random Forest  
- **Ensembles**: XGBoost, LightGBM  
- **Deep Learning**: MLPs, ANN, Hybrid Clinical-Genomic Networks  
- **Explainability**: SHAP, LIME, Feature Attribution tools

---

## 🔐 Ethics & Disclaimer

- This dataset is **fully anonymized**  
- Intended strictly for **academic and research** use  
- Users must ensure compliance with **ethical standards**, **institutional guidelines**, and **data governance policies**

---

## 📌 Citation

If you use this dataset in your research or publication, please cite the following:

@dataset{nidhi_gdm_2025,
author = {Nidhi Kulkarni},
title = {Gestational DM Clinical Features and Biomarkers Dataset},
year = 2025,
url = {https://www.kaggle.com/datasets/nidhik21/gestational-dm-clinical-features-and-biomarkers/data}
}


---

## 📫 Contact

For queries or collaborations, please contact: **nidhirk2113@gmail.com**
