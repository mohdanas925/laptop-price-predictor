# 💻 Laptop Price Predictor

A Machine Learning web application that predicts the price of a laptop based on its specifications. 
Users can enter laptop features such as brand, processor, RAM, storage, display characteristics, operating system, 
and graphics card to receive an estimated market price instantly.

## 📌 Project Overview
The Laptop Price Predictor uses a trained machine learning model to estimate laptop prices from hardware specifications. 
The project includes data preprocessing, model training, and a user-friendly web interface for making predictions.

This project demonstrates the complete machine learning workflow, from data cleaning and feature engineering to model deployment.

## 🚀 Features
Predicts laptop prices based on specifications
Interactive and easy-to-use web interface
Supports multiple laptop brands
Handles categorical and numerical features
Fast and accurate predictions using a trained ML model
Clean and responsive user interface


## ▶️ Run the Application
https://laptop-price-predictor0925.streamlit.app/

The application will open automatically in your browser.


## 🛠️ Tech Stack
### Programming Language
- Python
### Libraries
- Pandas
- NumPy
- Scikit-learn
- Pickle
- Streamlit
### Machine Learning
- Regression Algorithms
- Feature Engineering
- Data Preprocessing
- Model Evaluation

## 📂 Project Structure

```text
Laptop-Price-Predictor/
│
├── app.py
├── pipe1.pkl
├── df.pkl
├── requirements.txt
├── README.md
├── .gitignore
│
├── Dataset/
│   └── Laptop_data.csv
│
└── notebooks/
    └── model_training.ipynb
```

## 📊 Dataset Features

The model is trained using laptop specifications such as:

- Brand
- Laptop Type
- RAM
- Weight
- Touchscreen
- IPS Display
- Screen Size
- Screen Resolution
- CPU
- HDD
- SSD
- GPU
- Operating System
- Price (Target Variable)

## 📈 Machine Learning Workflow
1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Feature Encoding
6. Model Training
7. Model Evaluation
8. Model Serialization
9. Web Application Deployment


## 🎯 Input Parameters

The application accepts the following inputs:

- Brand
- Laptop Type
- RAM
- Weight
- Touchscreen
- IPS Display
- Screen Size
- Screen Resolution
- CPU
-  HDD
-  SSD
-  GPU
-  Operating System
  
### 📤 Output

The model predicts the estimated laptop price based on the selected specifications.


## 🔮 Future Improvements
- Improve prediction accuracy using advanced ensemble models
- Add support for the latest laptop models
- Integrate real-time market pricing APIs
- Visualize feature importance and prediction insights

## 👨‍💻 Author

Mohd Anas

If you found this project helpful, consider giving it a ⭐ on GitHub.
