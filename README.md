# 📊 Telecom Customer Churn Prediction System — End-to-End ML Deployment

An end-to-end machine learning project that predicts telecom customer churn and provides real-time predictions through a deployed web application.

This project demonstrates the complete data science lifecycle — from exploratory data analysis and model optimization to production deployment on AWS.

---

## 🚀 Project Overview

Customer churn is a major challenge for subscription-based businesses. This system identifies customers at high risk of leaving before they cancel, enabling proactive retention strategies.

### Key Highlights

- Exploratory Data Analysis (EDA) to uncover churn drivers
- Handling class imbalance using SMOTE / SMOTEENN
- Hyperparameter optimization with Optuna
- High-performance classification models
- Interactive Streamlit web application
- Cloud deployment on AWS EC2
- Real-time prediction capability

---

## 🧠 Machine Learning Pipeline

1. Data Cleaning & Preprocessing  
2. Feature Engineering (including tenure binning)  
3. Handling Imbalanced Data (SMOTE / SMOTEENN)  
4. Model Training & Evaluation  
5. Hyperparameter Tuning with Optuna  
6. Model Serialization (Joblib)  
7. Web App Development with Streamlit  
8. Deployment on AWS EC2  

---

## 🌐 Streamlit Web Application

The interactive web app allows users to input customer details and receive churn predictions instantly.

### Features

- User-friendly input interface
- Automated preprocessing pipeline
- Real-time predictions
- Churn probability score output
- Production-ready deployment

---

## 🛠️ Tech Stack

### Languages & Libraries

- Python  
- Pandas & NumPy  
- Scikit-learn  
- Imbalanced-learn  
- Optuna  
- Joblib  

### Modeling

- AdaBoost Classifier  
- SMOTE / SMOTEENN  
- Feature Scaling (StandardScaler)

### Deployment & Tools

- Streamlit  
- AWS EC2  
- Git  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```
### 2️⃣ Create Virtual Environment
```bash
python -m venv .venv
source .venv/bin/activate   # Linux / Mac
.venv\Scripts\activate      # Windows
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### ▶️ Run the Application Locally
```bash
streamlit run streamlit_app.py
```
### ☁️ AWS Deployment (Optional)

This project can be deployed on an AWS EC2 instance for public access.

Basic steps:
Launch an EC2 instance
Install Python and dependencies
Clone the repository
Install requirements
Run the Streamlit app
Configure security groups to allow access

### 📈 Model Output

The model provides:

Churn Prediction (Yes / No)
Probability of customer churn
This enables businesses to prioritize retention strategies for high-risk customers.

### 💼 Business Impact

Reduces revenue loss due to customer attrition
Supports targeted marketing campaigns
Enables data-driven decision making

Applicable across telecom, SaaS, banking, and subscription industries
