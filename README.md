Employee Attrition Prediction

An AI-powered machine learning project that predicts employee attrition using a **Random Forest model**. This application helps organizations identify employees at risk of leaving, enabling proactive 
decision-making.

---

## Features

* Predicts whether an employee is likely to leave or stay
* Uses **Random Forest Classifier** for accurate predictions
* Data preprocessing using Pandas
* Model training using Scikit-learn
* Interactive interface using Streamlit
* Saves trained model, scaler, and encoder for reuse


## Architecture

The system follows a machine learning pipeline:

1. Data Collection (HR Dataset)
2. Data Preprocessing (Cleaning, Encoding, Scaling)
3. Model Training (Random Forest Algorithm)
4. Model Saving (`model.pkl`, `scaler.pkl`, `encoder.pkl`)
5. Prediction using Streamlit App


## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Pickle

## ⚙️ Setup Instructions

1. Clone the repository:
   git clone https://github.com/your-username/Employee-attrition-prediction.git

2. Navigate to the project:
   cd Employee-attrition-prediction

3. Install dependencies:
   pip install -r requirements.txt

4. Run the training script (optional):
   python train.py

5. Start the application:
   streamlit run app.py


## Model Details

* Algorithm: **Random Forest Classifier**
* Library: Scikit-learn
* Handles both numerical and categorical features
* Provides robust and accurate predictions


This project demonstrates the application of machine learning in HR analytics to predict employee attrition and support better organizational decisions.
