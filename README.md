
# 🧬 Revolutionizing Liver Care

## 🩺 Liver Cirrhosis Prediction Web Application

This project is a **Flask-based web application** that predicts whether a patient is likely to have **liver cirrhosis** based on clinical input parameters. It uses a **machine learning model trained on real healthcare data** to provide real-time predictions.

---

## 📌 Key Features
- 🔎 Simple, interactive form for patient data entry
- 🤖 Backend ML model trained using Scikit-learn
- 🕒 Instant prediction: "Likely" or "Unlikely" to have liver cirrhosis
- 📊 Uses Pandas, Seaborn, and XGBoost for data processing and modeling
- ⚙️ Easily deployable locally
  
---

## 📁 Project Structure

liver-care/
├── app.py # Flask app for serving the web interface
├── model.py # Python script to train and export the ML model
├── model.pkl # Saved ML model (generated from model.py)
├── HealthCareData.xlsx # Dataset used for training
├── templates/
  └── index.html # HTML form for user input
  |__ result.html
├── static/ # Optional: for images, CSS, etc.
└── README.md # This documentation file

 ## required commands
- pip install flask pandas scikit-learn matplotlib seaborn xgboost imbalanced-leam
- python model.py
  
