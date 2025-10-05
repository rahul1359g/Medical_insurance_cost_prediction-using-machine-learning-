Medical Insurance Cost Prediction
📘 Project Description

This project predicts the medical insurance cost of an individual based on their personal and health-related factors using Machine Learning.
The goal is to help insurance companies and hospitals estimate the cost of coverage more accurately, and help customers understand how lifestyle and medical attributes affect their premiums.

🎯 Objectives

Analyze and understand the relationship between factors like age, gender, BMI, smoking habits, and region with insurance cost.

Build and train a Machine Learning Regression Model to predict medical charges.

Provide accurate and explainable predictions for insurance planning.

🧠 Tech Stack

Programming Language: Python

Libraries Used:

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

Algorithm: Linear Regression / Random Forest Regressor

📊 Dataset

Source: Kaggle - Medical Insurance Dataset

Attributes include:

age — Age of the individual

sex — Gender (male/female)

bmi — Body Mass Index

children — Number of dependents

smoker — Smoking habit (yes/no)

region — Residential area

charges — Insurance cost (target)

⚙️ Workflow

Data loading and cleaning

Exploratory Data Analysis (EDA)

Feature encoding (Label Encoding / One-Hot Encoding)

Model building using Regression

Model evaluation using MAE, MSE, and R² Score

Prediction on new input data

🧾 Example Prediction
Age	BMI	Smoker	Region	Predicted Cost
29	27.9	No	southeast	₹25,432
🚀 How to Run
# Clone this repository
git clone https://github.com/yourusername/MedicalInsuranceCostPrediction.git

# Navigate to project folder
cd MedicalInsuranceCostPrediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook MedicalInsuranceCostPrediction.ipynb

💡 Future Enhancements

Integrate model with a web interface (using Flask or Streamlit)

Add more features like exercise habits or medical history

Use advanced models (XGBoost, LightGBM, or Neural Networks)

👨‍💻 Developed By

Rahul Kumar Barik
AI/ML Enthusiast | B.Tech CSE | SmartMed Project Team
