Multiple Disease Prediction Model

Overview

The Multiple Disease Prediction Model is a machine learning-based web application that allows users to predict the likelihood of having various diseases, including:

Breast Cancer

Diabetes

Liver Disease

Kidney Disease

This project is developed using Flask for the backend and Machine Learning models trained on medical datasets.

Project Structure

Disease_project/
│── disease/
│── model/
│   ├── cancer.pkl
│   ├── diabetes.pkl
│   ├── kidney.pkl
│   ├── liver.pkl
│── static/
│   ├── Quotefancy images
│   ├── logo.png
│   ├── logo1.png
│── templates/
│   ├── breast_cancer.html
│   ├── diabetes.html
│   ├── home.html
│   ├── kidney.html
│   ├── liver.html
│   ├── main.html
│   ├── predict.html
│── app.py
│── Procfile.txt
│── python.txt
│── Breast_cancer.csv
│── diabetes.csv
│── indian_liver_patient.csv
│── kidney_disease.csv

Features

Predicts Breast Cancer, Diabetes, Liver Disease, and Kidney Disease Uses Machine Learning models trained on medical datasets Flask-based web application for easy user interaction✅ User-friendly Interface designed with Bootstrap✅ Provides a detailed prediction result based on input features

Datasets Used

Breast Cancer Dataset: Breast_cancer.csv

Diabetes Dataset: diabetes.csv

Liver Disease Dataset: indian_liver_patient.csv

Kidney Disease Dataset: kidney_disease.csv

Technologies Used

Python (Flask, Pandas, NumPy, Scikit-learn)

Machine Learning Models (Trained using Logistic Regression, Decision Tree, Random Forest, etc.)

HTML, CSS, JavaScript for Frontend

Bootstrap for styling

Heroku Deployment (Optional)

🏃‍♂️ How to Run the Project

1️⃣ Clone the Repository

git clone https://github.com/Gunjan-2005/AI-and-ML-Projects.git
cd AI-and-ML-Projects/Disease_project

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Flask Application

python app.py

4️⃣ Open in Browser

Go to http://127.0.0.1:5000/ to use the web application.

Future Enhancements

🔹 Improve accuracy with advanced ML models🔹 Add more diseases to the prediction system🔹 Deploy the project using Heroku/AWS/GCP

