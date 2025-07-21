# 📊 GPA 5 Prediction in Bangladesh SSC Exam (2001–2025)

## 🧠 Project Objective

This project aims to predict the number of GPA 5 scorers in the Bangladesh Secondary School Certificate (SSC) exam using historical data from 2001 to 2025. It applies various machine learning regression models to uncover patterns, evaluate accuracy, and enable future year forecasts based on inputs such as:
- Total Examinees
- Pass Rate
- Year

---

## 📁 Dataset Description

| Column Name        | Description                                   |
|--------------------|-----------------------------------------------|
| `Year`             | Academic year of the SSC exam                 |
| `Total_Examinees`  | Number of students who appeared               |
| `Pass_Rate`        | Overall pass percentage for the year          |
| `GPA_5_Count`      | Number of students who scored GPA 5           |

---

## ⚙️ Technologies Used

- **Python 3.11**
- **Pandas**, **NumPy** – Data preprocessing & manipulation  
- **Matplotlib**, **Seaborn** – Visualization  
- **Scikit-learn** – Model building and evaluation  
- **Google Colab** – Development environment  
- **Streamlit (optional)** – For interactive app (tested)

---

## 📌 Key Features

- Data cleaning and transformation  
- Exploratory Data Analysis (EDA)  
- Outlier detection & correlation analysis  
- Trained multiple ML models:  
  - Linear Regression  
  - Ridge Regression  
  - Lasso Regression  
  - Decision Tree Regressor  
  - Random Forest Regressor  
- Prediction for future values using user inputs  
- Model performance visualization (R² score, RMSE comparison)

---

## 📈 Model Performance Snapshot

| Model                | R² Score | RMSE     |
|----------------------|----------|----------|
| Linear Regression    | 0.8975   | 16001.12 |
| Ridge Regression     | 0.8970   | 16041.71 |
| Lasso Regression     | 0.8975   | 16001.12 |
| Decision Tree        | 0.9148   | 14583.77 |
| **Random Forest**    | **0.9953** | **3431.89** |

> 🔍 Random Forest outperformed others and was selected for final predictions.

---

## 📊 Sample Visualizations

- Examination trends (2001–2025)
- Pass rate progression over time
- Yearly GPA 5 distribution
- Model comparison chart

---

## 📤 Future Work

- Build a real-time dashboard with Streamlit or Power BI  
- Extend prediction to other education boards in South Asia  
- Incorporate socio-economic variables (e.g., school type, region)

---

## 🧑‍💻 Author

**Kumari Shivangi**  
Data Science Trainee – AlmaBetter  
📅 Report Date: July 22, 2025  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/kumarishivangi7)

---

## 📜 Disclaimer

This project is educational and exploratory in nature. Predictions are based on historical trends and assumptions. Data inconsistencies or policy changes may affect the model’s accuracy.

