# 📊 End-to-End Machine Learning Project on Student Performance Index

This repository presents a complete **End-to-End Machine Learning pipeline** to predict and analyze a **Student Performance Index (SPI)**. It includes data preprocessing, EDA, model building, evaluation, tuning, and deployment using Flask.

---

## 🚀 Project Overview

The goal is to build a predictive model that estimates student performance based on various academic, demographic, and lifestyle features. This project covers:

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering & Selection  
- Model Training and Evaluation  
- Hyperparameter Tuning  
- Model Deployment with Flask Web App

---



---

## 📊 Dataset Summary

- **Name:** Student Performance Dataset  
- **Source:** Public CSV (included in `dataset/`)  
- **Key Features:**
  - Demographics: Gender, Age, Address Type
  - Academics: Study Time, Past Failures, Parental Education
  - Lifestyle: Internet Access, Absences, Health
  - Grades and Test Scores

---

## 🧠 Technologies Used

| Category              | Tools/Libraries                             |
|-----------------------|---------------------------------------------|
| Language              | Python 3.10                                  |
| Data Manipulation     | Pandas, NumPy                                |
| Visualization         | Matplotlib, Seaborn                          |
| Machine Learning      | Scikit-learn, XGBoost, RandomForest          |
| Web Framework         | Flask                                        |
| Frontend              | HTML, CSS (Bootstrap optional)              |
| Deployment            | Localhost / Render / Docker (Optional)      |

---

## 📈 Model Performance

Models used and tested:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

📌 **Best Accuracy (R² Score):** Random Forest/XGBoost with > 85% on test data

---



## 📓 Notebooks

- 📘 [1_Data_Analysis.ipynb](notebooks/1_Data_Analysis.ipynb) – Data loading, cleaning, EDA  
- 📗 [2_Model_Training.ipynb](notebooks/2_Model_Training.ipynb) – Model selection & training  
- 📙 [3_Model_Evaluation.ipynb](notebooks/3_Model_Evaluation.ipynb) – Performance evaluation & metrics  

---

## 🧪 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/wasif23ahad/End-to-End-Machine-Learning-Project-on-StudentPerformanceIndex.git
   cd End-to-End-Machine-Learning-Project-on-StudentPerformanceIndex 
   ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt 
    ```

3. Run the Flask app:
    ```bash

    python app.py 
    ```

4. Open your web browser and navigate to http://localhost:5000 to access the web app.

📬 Author
Mohammad Wasif Ahad
📧 wasifahad300@gmail.com
🔗 GitHub : https://github.com/wasif23ahad



