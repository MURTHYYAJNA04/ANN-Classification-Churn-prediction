# Customer Churn Prediction Using Artificial Neural Networks (ANN)

## Project Overview

This project predicts whether a bank customer is likely to leave the bank using an Artificial Neural Network (ANN) built with TensorFlow and Keras. A Streamlit web application allows users to enter customer information and obtain a churn prediction.

## Live Application

**[Launch Customer Churn Prediction App](https://ann-classification-churn-prediction-nmkf5iem9jkqsmbpxwfhqo.streamlit.app/)**

## Technologies Used

- Python
- TensorFlow and Keras
- Pandas and NumPy
- Scikit-learn
- Streamlit
- Pickle
- Git and GitHub

## Project Workflow

1. Load and explore the customer churn dataset.
2. Preprocess customer data.
3. Encode categorical variables such as Geography and Gender.
4. Scale numerical features using the trained scaler.
5. Train an Artificial Neural Network.
6. Save the trained model, encoders, and scaler.
7. Deploy the prediction application using Streamlit Community Cloud.

## Features

The application accepts the following customer details:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Account Balance
- Number of Products
- Credit Card Ownership
- Active Membership
- Estimated Salary

The model returns a prediction indicating whether the customer is likely to churn.

## Repository Structure

```text
ANN-Classification-Churn-prediction/
├── app.py
├── model.h5
├── label_encoder_gender.pkl
├── Onehotencoder_Geography.pkl
├── sc.pkl
├── requirements.txt
├── runtime.txt
├── Churn_Modelling.csv
├── experiments.ipynb
├── README.md
└── LICENSE
```

## Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/murthyyajna04/ANN-Classification-Churn-prediction.git
cd ANN-Classification-Churn-prediction
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
```

Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch the application

```bash
streamlit run app.py
```

## Model and Preprocessing

The application loads the trained ANN model and previously fitted preprocessing objects. Input features must follow the same column order and preprocessing steps used during model training.

## Future Improvements

- Display churn probability and confidence-related information.
- Improve model evaluation using precision, recall, F1-score, and ROC-AUC.
- Add model explainability.
- Enhance the user interface and customer insights.

## Author

**Murthy Yajna**

Machine Learning | Deep Learning | Python | Data Analytics | Streamlit

## Disclaimer

This project is for educational and demonstration purposes. Predictions are estimates and should not be treated as definitive financial decisions.
