# Healthcare-Premium-Prediction-ML-Project
machine learning healthcare premium prediction app

# 🏥 Healthcare Premium Prediction (Regression)
# 1. Project Overview

This project predicts healthcare insurance premiums using machine learning. The goal is to estimate a person’s premium amount based on demographic and lifestyle features such as age, BMI, smoking habits, and other relevant factors.

The project includes the full ML pipeline: data collection, cleaning, exploratory data analysis, feature engineering, model training, fine-tuning, and deployment as an interactive Streamlit web application.

To improve prediction accuracy, the dataset is segmented by age group and separate models are trained for young and adult customers.

# 2. Problem Statement

Healthcare insurance companies need accurate premium predictions to reduce financial risk and provide fair pricing to customers.

Traditional pricing methods may fail to capture complex relationships between customer attributes and premium costs. This project aims to build a regression model that predicts insurance premiums with high accuracy, helping insurers make data-driven pricing decisions.
## ⚙️ Project Workflow
1. Data cleaning & preprocessing
2. Exploratory data analysis (EDA)
3. Feature engineering
5. Model training (Logistic Regression / XGBoost)
6. Model evaluation (ROC-AUC, KS, Gini)
7. Model serialization
8. Streamlit deployment
# 3. Features

-age
-number_of_dependents
- income_in_lakhs
- genetic_risk
- gender
- smoking_status
- marital_status
- region
- medical_history
- employment_status
- 
# 4. Tech Stack

Python

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

Joblib

Streamlit

# 5. Dataset Information

Initial dataset : premiums.xlsx

After segmentation: 
1. Young customers (age ≤ 25): premiums_young_with_gr

2. Adult customers (age > 25): premiums_rest

The dataset contains customer attributes used to predict healthcare insurance premiums.

# 6. Installation / Setup
Step 1: Clone the repository
git clone https://github.com/waghvaishnav/Healthcare-Premium-Prediction-ML-Project.git
cd healthcare-premium-prediction

Step 2: Create virtual environment (optional)
python -m venv venv
venv\Scripts\activate

Step 3: Install dependencies
pip install -r requirements.txt

Step 4: Run the Streamlit app
streamlit run main.py

# 7. Usage

Open the Streamlit app in your browser

Enter customer details (age, BMI, lifestyle, etc.)

Click Predict

The model returns the estimated healthcare premium instantly

This app demonstrates real-time ML inference.

# 8. Screenshots / Demo

![App Screenshot](https://raw.githubusercontent.com/waghvaishnav/Healthcare-Premium-Prediction-ML-Project/714c80662a1b71d5c8508b5a2db749d0447307ab/Screenshot%202026-02-12%20231139.png)

# 9. Results / Model Performance

# Model accuracy: 98%

Regression-based premium prediction

Error analysis performed to validate model reliability

Age-based segmentation improved performance

Reduced prediction error through fine-tuning

Key insights:

Smoking and BMI significantly impact premiums

Younger customers show different premium patterns

Segmented modeling improves prediction stability
