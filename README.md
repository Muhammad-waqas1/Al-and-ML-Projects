# 🚀 Multiple Disease Prediction Model  

## 🏥 Overview  

The **Multiple Disease Prediction Model** is a **machine learning-powered** web application that predicts the likelihood of having various diseases, including:  

✔ **Breast Cancer**  
✔ **Diabetes**  
✔ **Liver Disease**  
✔ **Kidney Disease**  

This project utilizes **Flask** for the backend and **Machine Learning models** trained on medical datasets to provide accurate disease predictions.  


## 📂 Project Structure  
```
Disease_project/  
│── disease/  
│── model/  
│ ├── cancer.pkl  
│ ├── diabetes.pkl  
│ ├── kidney.pkl  
│ ├── liver.pkl  
│── static/  
│ ├── Quotefancy images  
│ ├── logo.png  
│ ├── logo1.png  
│── templates/  
│ ├── breast_cancer.html  
│ ├── diabetes.html  
│ ├── home.html  
│ ├── kidney.html  
│ ├── liver.html  
│ ├── main.html  
│ ├── predict.html  
│── app.py  
│── Procfile.txt  
│── python.txt  
│── Breast_cancer.csv  
│── diabetes.csv  
│── indian_liver_patient.csv  
│── kidney_disease.csv  

```
## ✨ Features  

✅ **Predicts multiple diseases** – Breast Cancer, Diabetes, Liver Disease, and Kidney Disease  
✅ **Trained ML models** – Uses **Logistic Regression, Decision Tree, Random Forest**, etc.  
✅ **Flask-based Web App** – Easy-to-use interface for users  
✅ **User-friendly design** – Styled with **Bootstrap**  
✅ **Detailed Predictions** – Displays results based on input medical parameters  



## 📊 Datasets Used  

| Disease        | Dataset |
|---------------|---------|
| **Breast Cancer** | `Breast_cancer.csv` |
| **Diabetes** | `diabetes.csv` |
| **Liver Disease** | `indian_liver_patient.csv` |
| **Kidney Disease** | `kidney_disease.csv` |


## 🛠 Technologies Used  

- **Backend**: Flask, Python  
- **Machine Learning**: Scikit-learn, Pandas, NumPy  
- **Frontend**: HTML, CSS, JavaScript  
- **Styling**: Bootstrap  
- **Deployment** (Optional): Heroku / AWS / GCP  


## 🏃‍♂️ How to Run the Project  

### 1️⃣ Clone the Repository  

    git clone https://github.com/Gunjan-2005/AI-and-ML-Projects.git
    cd AI-and-ML-Projects/Disease_project
### 2️⃣ Install Dependencies

    pip install -r requirements.txt
### 3️⃣ Run the Flask Application

    python app.py
### 4️⃣ Open in Browser  
Go to: http://127.0.0.1:5000/

## 🚀 Future Enhancements  
🔹 Improve prediction accuracy with advanced ML models  
🔹 Expand the system to include more diseases  
🔹 Deploy the application on Heroku, AWS, or GCP  
🔹 Enhance UI/UX for a better user experience

## 💡 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.
