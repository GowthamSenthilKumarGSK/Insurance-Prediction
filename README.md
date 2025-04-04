# Prediction-Insurance

# 🩺 Insurance Cost Prediction

This project aims to predict medical insurance charges based on personal and demographic features such as age, sex, BMI, number of children, smoking status, and region. It includes exploratory data analysis (EDA), preprocessing, visualization, and machine learning model building.

---

## 📂 Dataset

The dataset used is `insurance.csv`, which contains the following columns:

- `age`: Age of the primary beneficiary
- `sex`: Insurance contractor gender (female, male)
- `bmi`: Body mass index
- `children`: Number of children covered by health insurance
- `smoker`: Smoking status (yes/no)
- `region`: Residential area in the US (northeast, southeast, etc.)
- `charges`: Individual medical costs billed by health insurance

---

## 🧰 Technologies Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib (Visualizations)
- Plotly (Interactive Visualizations)
- Scikit-learn (ML Models & Preprocessing)
- `datasist` (EDA Automation - optional)

---

## 📊 Exploratory Data Analysis

- Univariate and bivariate analysis
- KDE and histogram plots for distribution of charges
- Correlation heatmap
- Outlier detection (box plots for BMI and charges)
- Relationship between smoking status and charges

---

## 🧹 Preprocessing Steps

- Handling missing values (if any)
- Encoding categorical variables using `LabelEncoder` or `get_dummies`
- Feature scaling using `StandardScaler`

---

## 🤖 Machine Learning Models

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Performance Metrics: MAE, MSE, RMSE, R² Score

---

## ✅ Results

- Model comparison based on accuracy and RMSE
- Visual plots showing actual vs predicted charges
- Random Forest typically performs the best in this regression problem

---
