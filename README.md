# 💳 Credit Risk Prediction — Machine Learning Project

This project focuses on building a machine learning model to predict **credit risk** — whether a loan applicant is likely to **default** or be **low risk**. Using a real-world financial dataset, the project covers data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling.

---

## 🧾 Dataset

- **Name:** Credit Risk Dataset  
- **Target Variable:** Loan Status (e.g., `Risk`, `No Risk`)  
- **Features Include:** Age, Income, Employment Status, Credit History, Loan Amount, Purpose, etc.

---

## 🔧 Preprocessing Steps

- Handled missing values and incorrect formats
- Converted categorical features using **Label Encoding** or **One-Hot Encoding**
- Scaled numeric features using **StandardScaler**
- Removed irrelevant or duplicate columns (if any)
- Split data into **training and test sets**

---

## 📊 Exploratory Data Analysis (EDA)

- Analyzed target class distribution (risky vs non-risky loans)
- Visualized feature impact (e.g., income, credit score, employment) on credit risk
- Correlation matrix to identify key predictors
- Boxplots, histograms, and bar charts to explore feature distributions

---

## 🤖 Predictive Modeling

Built and evaluated classification models to predict credit risk:

- **Logistic Regression** (baseline)
- (Optional: You can also mention Random Forest / XGBoost if used)

### 🔍 Evaluation Metrics:

- **Accuracy**
- **Precision / Recall / F1-Score**
- **Confusion Matrix**

Model selection was based on balancing **true positives (detecting high risk)** and **false negatives (misclassifying risky customers)** — crucial in financial applications.

---

## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn** for data visualization
- **Scikit-learn** for preprocessing and machine learning

---

## 🚀 Future Improvements

- Test with advanced models like **Random Forest**, **XGBoost**, or **LightGBM**
- Add feature selection techniques for better model simplicity
- Deploy model as an API or Streamlit app for real-time predictions
- Add explainability (e.g., SHAP values) to make decisions more transparent

---

