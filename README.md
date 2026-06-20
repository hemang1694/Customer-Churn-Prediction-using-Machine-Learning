# Customer Churn Prediction using Machine Learning

## 📌 Overview

Customer Churn Prediction is a Machine Learning project that helps businesses identify customers who are likely to discontinue their services. Retaining existing customers is often more cost-effective than acquiring new ones, making churn prediction a critical business problem.

This project uses the Telco Customer Churn Dataset and applies data preprocessing, exploratory data analysis (EDA), machine learning models, and SHAP explainability techniques to predict customer churn and generate actionable business insights.

---

## 🎯 Objectives

- Predict whether a customer will churn or stay.
- Analyze factors influencing customer churn.
- Compare machine learning models for churn prediction.
- Interpret model predictions using SHAP explainability.

---

## 📂 Dataset

The project uses the **Telco Customer Churn Dataset** containing:

- Customer demographics
- Service subscriptions
- Account information
- Billing details
- Churn status

### Target Variable

| Value | Meaning |
|---------|---------|
| 1 | Customer Churned |
| 0 | Customer Retained |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- SHAP
- Google Colab

---

## 🔄 Project Workflow

### 1. Data Preprocessing

- Load dataset
- Handle missing values
- Convert data types
- Encode categorical features
- Remove unnecessary columns

### 2. Exploratory Data Analysis (EDA)

- Churn distribution analysis
- Monthly charges analysis
- Customer tenure analysis
- Data visualization

### 3. Model Building

The following machine learning algorithms were implemented:

#### Logistic Regression

A simple and interpretable classification model used as a baseline.

#### Random Forest Classifier

An ensemble learning method that combines multiple decision trees to improve prediction accuracy.

---

## 📊 Model Evaluation

The models were evaluated using:

- Accuracy Score
- ROC-AUC Score
- Classification Report
- Confusion Matrix

---

## 🔍 Explainable AI (XAI)

SHAP (SHapley Additive Explanations) was used to understand how different features contribute to churn predictions.

Benefits:

- Improved model transparency
- Better business decision making
- Feature importance analysis

---

## 📈 Key Insights

- Customers with shorter tenure are more likely to churn.
- Higher monthly charges are associated with higher churn rates.
- Customers on month-to-month contracts show greater churn probability.
- Long-term customers tend to remain loyal.

---

## 💡 Business Recommendations

- Offer loyalty rewards for long-term customers.
- Encourage annual subscription plans.
- Improve customer support services.
- Provide personalized retention offers to high-risk customers.

---

## 📁 Project Structure

```text
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
├── requirements.txt
└── images/
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

Move to the project directory:

```bash
cd customer-churn-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

Run the Jupyter Notebook or Google Colab notebook:

```bash
jupyter notebook Customer_Churn_Prediction.ipynb
```

Follow the notebook cells sequentially to:

- Preprocess data
- Train models
- Evaluate performance
- Generate SHAP explanations

---

## 📋 Requirements

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
shap
```

---

## 🎓 Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Exploratory Data Analysis (EDA)
- Classification algorithms
- Model evaluation methods
- Explainable AI using SHAP
- Business-oriented machine learning applications

---

## 👨‍💻 Author

**Hemang Chouhan**

B.Tech CSE (AI & DS)
JECRC University, Jaipur

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a star!
