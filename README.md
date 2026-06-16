# 📊 Adult Income Classification Project

## 🚀 Overview
This project is a Machine Learning classification task that predicts whether an individual's income exceeds 50K per year based on census data.

It includes a full end-to-end pipeline:
- Data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training
- Model evaluation & comparison

---

## 📂 Dataset
The dataset is the **Adult Income Dataset**.

It contains demographic and employment-related features such as:
- Age
- Workclass
- Education
- Occupation
- Marital Status
- Relationship
- Gender
- Capital Gain / Loss
- Hours per week
- Native Country

🎯 **Target Variable:**
- `<=50K` → 0  
- `>50K` → 1  

---

## 🛠 Tools & Technologies

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Plotly
- YData Profiling

---

## 📊 Exploratory Data Analysis (EDA)

Key steps performed:
- Missing value detection & handling
- Duplicate removal
- Feature distribution analysis
- Correlation heatmap
- Outlier detection using boxplots

---

## ⚙️ Data Preprocessing

Applied transformations:
- Dropped irrelevant columns
- Replaced unknown values
- Grouped categorical variables
- One-Hot Encoding for categorical features
- Log transformation for:
  - Capital Gain
  - Capital Loss
- Outlier removal using IQR method
- Feature scaling using StandardScaler

---

## 🤖 Machine Learning Models

The following models were trained and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier

---

## 📈 Evaluation Metric

- Accuracy Score

---

## 🏆 Results

All models were evaluated and compared based on accuracy to select the best-performing classifier.

---

## 🚀 How to Run

```bash
git clone https://github.com/Shahdsafwat/adult-income.git
cd adult-income
pip install -r requirements.txt
jupyter notebook diabetes_dataset.ipynb
