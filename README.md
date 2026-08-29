# wine-quality-classification-knime

# 🍷 Wine Quality & Type Classification using KNIME

An end-to-end Machine Learning data pipeline built using **KNIME Analytics Platform** to analyze chemical properties of red and white wines and classify them into quality categories.

---

## 📌 Project Overview
The objective of this project is to process chemical attributes of wine datasets, apply preprocessing techniques, and construct a predictive model using **Random Forest Classifier** to accurately distinguish between high-quality and low-quality wines based on their chemical composition.

---

## 📊 Dataset Information
The dataset used in this project consists of two separate CSV files:
- **`winequality-red.csv`**: Red wine variants (1,599 instances)
- **`winequality-white.csv`**: White wine variants (4,898 instances)

### Input Features (Physicochemical Properties):
1. **Fixed Acidity**: Most acids involved with wine
2. **Volatile Acidity**: Amount of acetic acid in wine
3. **Citric Acid**: Adds 'freshness' and flavor to wines
4. **Residual Sugar**: Amount of sugar remaining after fermentation stops
5. **Chlorides**: Amount of salt in the wine
6. **Free Sulfur Dioxide**: Prevents microbial growth and oxidation
7. **Total Sulfur Dioxide**: Amount of free and bound forms of $SO_2$
8. **Density**: Density of water depending on the percent alcohol and sugar content
9. **pH**: Describes how acidic or basic a wine is (0-14)
10. **Sulphates**: Additive which can contribute to sulfur dioxide levels
11. **Alcohol**: The percent alcohol content of the wine

### Target Variable:
- **`quality_label`**: Categorical output created using `Rule Engine`
  - **Good**: Quality rating $\ge$ 6
  - **Low**: Quality rating < 6

---

## ⚙️ Workflow & Architecture in KNIME

The KNIME workflow consists of the following data processing pipeline:
