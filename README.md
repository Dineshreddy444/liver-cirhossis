Liver Cirrhosis Prediction System

This project is a Machine Learning web application that predicts the likelihood of liver cirrhosis using patient health and alcohol consumption data. The model is built using Logistic Regression and deployed through a Flask web application, allowing users to enter medical parameters and receive an instant prediction.

Features
Predicts the likelihood of liver cirrhosis.
User-friendly web interface built with Flask.
Trained using Logistic Regression.
Handles imbalanced datasets using SMOTE.
Uses patient health parameters for prediction.
Provides real-time prediction results.


Technologies Used
Python
Flask
Pandas
NumPy
Scikit-learn
SMOTE (Imbalanced-learn)
HTML
CSS
Pickle


Input Parameters
Age
Duration of Alcohol Consumption (Years)
Quantity of Alcohol Consumption (Quarters/Day)
Total Cholesterol (TCH)
Triglycerides (TG)
LDL
HDL
Hemoglobin
SGOT/AST
SGPT/ALT



Machine Learning Workflow
Load and clean the healthcare dataset.
Handle missing values and normalize labels.
Balance the dataset using SMOTE.
Train a Logistic Regression model.
Save the trained model using Pickle.
Deploy the model using Flask for real-time predictions.

Project Structure
Liver-Cirrhossis-main/
│── project files/
│   ├── app.py
│   ├── model.py
│   ├── model.pkl
│   ├── HealthCareData.xlsx
│   ├── templates/
│   └── static/
│
├── training/
├── document/
└── Demo video/



GitHub Topics :
machine-learning
python
flask
logistic-regression
healthcare
liver-cirrhosis
scikit-learn
prediction-system
medical-ai
smote


