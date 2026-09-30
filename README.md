# Credit Risk Prediction System

A machine learning-based Credit Risk Prediction System that predicts the credit risk of a loan applicant using financial and personal information.

The project uses a trained machine learning model served through a FastAPI backend with an interactive HTML, CSS, and JavaScript frontend.

## Features

- Credit risk prediction using Machine Learning
- FastAPI REST API
- Interactive web interface
- Pydantic input validation
- Pre-trained ML model
- Custom decision threshold
- CORS support
- Static frontend using HTML, CSS and JavaScript
- Ready for deployment using Render

## Technologies Used

- Python
- FastAPI
- Pydantic
- Pandas
- Scikit-learn
- Joblib
- HTML
- CSS
- JavaScript

## Project Structure

```text
loan_/
│
├── static/
│   ├── index.html
│   ├── script.js
│   └── style.css
│
├── best_threshold.pkl
├── credit_risk_dataset.xls
├── credit_risk_model.pkl
├── main.py
├── render.yaml
├── requirements.txt
├── runtime.txt
└── README.md
