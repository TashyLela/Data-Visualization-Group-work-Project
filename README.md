# Annual Income Prediction – Data Visualization Project

## Project Overview
This project focuses on exploring and visualizing a dataset to predict whether an individual's annual income exceeds a certain range. Using machine learning techniques and extensive data visualization, the goal is to build interpretable and accurate predictive models.

## Dataset
The dataset contains demographic and personal information about individuals, such as:

- Age
- Workclass
- Education
- Marital status
- Occupation
- Relationship
- Race
- Sex
- Capital gain/loss
- Hours per week
- Native country

### Target Variable:
- **Classification Task:** Whether income >50K (Yes/No)

Source: [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult)

---

## Data Preprocessing

- **Missing value handling**
- **Label encoding** for categorical variables
- **Outlier detection and correction** using IQR
- **Balancing the dataset**
- **Train-test split**

---

## Exploratory Data Analysis (EDA)

- Histograms and boxplots for feature distribution
- Correlation heatmap
- Bar plots for categorical variable impact
- Income distribution visualization

---

## Models Used

### **Classification:**
- `RandomForestClassifier`
- `XGBClassifier`

** Hyperparameter tuning:**  
Performed with `GridSearchCV` using `f1_macro` as scoring metric.

**Evaluation Metrics:**
- Accuracy
- Precision, Recall, F1-score (weighted & macro)
- Confusion Matrix
- Classification Report

## Visualizations

- Confusion matrices (heatmap)
- Feature importance plot
- Distribution plots of key features

---

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
-Random Forest
---
