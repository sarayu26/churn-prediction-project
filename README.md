# 📉 Customer Churn Prediction Dashboard

An end-to-end machine learning project that predicts customer churn using Python (scikit-learn) and visualizes insights through a Power BI interactive dashboard.  
This project combines data science with business intelligence to help companies identify and prevent customer attrition.

---

## 📁 Project Structure

Customer-Churn-Prediction-PowerBI-Python/
├── data/
│ ├── raw_churn_data.csv
│ ├── cleaned_churn_data.csv
│ └── churn_predictions_for_dashboard.csv
├── notebooks/
│ └── churn_prediction_model.ipynb
├── PowerBI/
│ └── Customer_Churn_Dashboard.pbix
├── assets/
│ ├── dashboard_screenshot_1.png
│ └── dashboard_screenshot_2.png
├── .gitignore
├── README.md
├── requirements.txt
└── LICENSE


---

## 🧠 Project Overview

- **Goal:** Predict which telecom customers are likely to churn.
- **Tools Used:**
  - 🐍 Python (pandas, scikit-learn, matplotlib, seaborn)
  - 📊 Power BI (for interactive dashboard)
- **ML Models:** Logistic Regression, Random Forest
- **Output:** A `.csv` file of predictions used in a Power BI report

---

## 🔍 Key Features

- End-to-end churn prediction pipeline:
  - Data preprocessing
  - EDA (Exploratory Data Analysis)
  - Feature engineering
  - Model training & evaluation
  - Exporting predictions to `.csv`
- Power BI dashboard for business insights:
  - Customer churn breakdown
  - Feature importance
  - Churn probability distribution
  - Filtering by gender, senior status, tenure, etc.

---

## 📸 Dashboard Preview

![Churn Dashboard](assets/dashboard_screenshot_1.png)

---

## 🚀 How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Customer-Churn-Prediction-PowerBI-Python.git
cd Customer-Churn-Prediction-PowerBI-Python

2. Install Python Dependencies
pip install -r requirements.txt

3. Run Jupyter Notebook
Open the notebook and run it step-by-step to:

Clean data
Train models
Generate predictions

jupyter notebook notebooks/churn_prediction_model.ipynb

4. Load Predictions into Power BI
Open PowerBI/Customer_Churn_Dashboard.pbix
Make sure the CSV path points to data/churn_predictions_for_dashboard.csv
Refresh the dashboard
📦 Requirements
Python 3.7+
Jupyter
scikit-learn
pandas
matplotlib
Power BI Desktop
(See requirements.txt for the full list)

📄 License
This project is licensed under the MIT License.

✨ Credits
Dataset: Telco Customer Churn (Kaggle )

Built with 💻 by [Sarayu Mamidyala]

