# Crop-Production-Prediction-ML-Project
Machine Learning project predicting agricultural crop production in India using real datasets from data.gov.in.

### 🏢 Company  
**UniConverge Technologies PVT.LTD (UCT)** — Machine Learning Internship  

---

## 📘 Project Overview
This project focuses on predicting **agricultural crop production in India** using machine learning techniques.  
The dataset (2001–2014) from [data.gov.in](https://data.gov.in/) includes information such as crop type, cost, yield, and region.  
The objective is to develop a model that can estimate crop production and help improve agricultural planning and decision-making.

---

## 🎯 Problem Statement
Accurate prediction of crop production is challenging due to variable climate, soil, and resource conditions.  
This project applies machine learning to create a predictive model that supports better agricultural resource management.

---

## 🧩 Implementation Details

**1️⃣ Data Preparation**  
- Combined five datasets from 2001–2014.  
- Cleaned, formatted, and merged data into `final_crop_dataset.csv`.

**2️⃣ Model Development**  
- Used **Linear Regression** for prediction.  
- Evaluated using R², MAE, and RMSE metrics.  

**3️⃣ Visualization**  
- Scatter plot for *Actual vs Predicted Production*.  
- Bar plot for feature coefficients.

---

## 📊 Results

| Metric | Value |
|:-------|:------|
| R² Score | 0.88 |
| MAE | 125.34 |
| RMSE | 168.92 |

**Key Insight:**  
Yield and Cost of Cultivation have the most influence on total crop production.  

---

## 🧠 Learnings
- Gained practical skills in data cleaning, preprocessing, and model evaluation.  
- Learned to interpret regression results and visualize prediction performance.  
- Understood how machine learning can assist in agricultural planning and analytics.

---

## 📂 Repository Structure
Crop_Production_Prediction/
│
├── data/
│ ├── raw/
│ └── processed/final_crop_dataset.csv
│
├── notebooks/
│ ├── 01_data_preparation.ipynb
│ └── 02_model_training.ipynb
│
├── models/
│ └── crop_model.pkl
│
├── outputs/
│ ├── figures/
│ │ ├── actual_vs_predicted.png
│ │ └── feature_importance.png
│ ├── metrics.txt
│
├── reports/
│ └── project4_report.docx
│
└── README.md

yaml
Copy code

---

## 🧰 Tools & Libraries
- Python  
- Jupyter Notebook  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  

---

## 🔍 Future Scope
- Implement **Random Forest** and **XGBoost** for better accuracy.  
- Add features like rainfall, soil data, and temperature.  
- Develop a dashboard for data visualization and farmer insights.

---

## 👨‍💻 Author
**Pavan Balasaheb Kakade**  
Machine Learning Intern — Universal Cloud Tech (UCT)

---

## 🪴 Acknowledgment
Special thanks to **UniConverge Technology pvt.Ltd (UCT)** for providing mentorship and support throughout this internship project.
