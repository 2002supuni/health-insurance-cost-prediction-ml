# Health Insurance Cost Prediction Using Machine Learning

## Project Overview
This project predicts health insurance costs using machine learning techniques based on demographic and health-related features. The project covers the complete ML pipeline, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and deployment.

After experimenting with multiple models, XGBoost was selected as the final model due to its superior performance.

An interactive web application was developed using Streamlit to provide real-time insurance cost predictions.

---

## Dataset Features
The dataset includes the following features:
- Age
- Gender
- Body Mass Index (BMI)
- Number of children
- Blood pressure
- Diabetic status
- Smoking status

The target variable is the estimated insurance payment amount.

---

## Model Used
- **XGBoost Regressor**

XGBoost was chosen based on evaluation metrics and overall prediction accuracy.

---

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Streamlit

---

## How to Run the App
1. Clone the repository:
   ```bash
   git clone https://github.com/2002supuni/health-insurance-cost-prediction-ml.git
   
2. Navigate to the project directory:
   cd health-insurance-cost-prediction-ml

3. Install required libraries:
   pip install -r requirements.txt

4. Run streamlit app:
   streamlit run app.py



