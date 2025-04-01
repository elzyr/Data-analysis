# Predict Students' Dropout and Academic Success 🎓

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

## 📖 Project Description

This project explores and predicts student outcomes by analyzing a rich dataset containing academic, demographic, and socio-economic features. The primary goal is to classify students into one of three categories at the end of the normal course duration:
- **Dropout**  
- **Enrollment/Continued Studies**  
- **Graduation**

The complete analysis pipeline includes data preprocessing, exploratory data analysis (EDA), feature selection, and applying machine learning algorithms (such as Random Forest and SVM) for predictive modeling.

---

## 📊 Dataset Description

The dataset originates from the UCI Machine Learning Repository and contains numerous features related to student profiles. Some example features include:

| Feature Name                      | Type         | Description                                                                                                                         | Missing Data |
|-----------------------------------|--------------|-------------------------------------------------------------------------------------------------------------------------------------|--------------|
| Marital Status                    | Categorical  | 1 – Single, 2 – Married, 3 – Widower, 4 – Divorced, 5 – Cohabitating, 6 – Legally Separated                                          | No           |
| Application Mode                  | Categorical  | Codes representing different application types (e.g., general quota, international student, transfer, change of course)              | No           |
| Application Order                 | Categorical  | Order of application preference (0 for first choice, up to 9 for last choice)                                                       | No           |
| Course                            | Categorical  | Numeric codes with corresponding study programs (e.g., Technologies in Biofuel Production, Nursing, Management, etc.)                | No           |
| Daytime/Evening Attendance        | Categorical  | 1 – Daytime, 0 – Evening                                                                                                             | No           |
| Previous Qualification (grade)    | Continuous   | Grade achieved in the previous qualification (scale 0–200)                                                                           | No           |
| Admission Grade                   | Continuous   | Admission exam grade (scale 0–200)                                                                                                   | No           |
| Curricular Units (1st & 2nd sem)    | Continuous   | Number of program units enrolled, credited, evaluated, approved, and average grade per semester                                        | No           |
| Socio-economic indicators         | Continuous   | Unemployment rate, Inflation rate, GDP                                                                                             | No           |
| **Target**                        | Categorical  | Outcome category: predicts dropout, enrollment (continuation) or graduation                                                         | –            |

*For a complete description of all features, please refer to the detailed notes within the `projekt.ipynb` notebook.*

**Data Source:**  
[Predict Students' Dropout and Academic Success](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)

---

## 🛠️ Technologies Used

- **Programming Language:** Python 🐍
- **Libraries:**
  - `pandas` – Data manipulation and analysis
  - `numpy` – Numerical computations
  - `matplotlib` & `seaborn` – Data visualization
  - `scikit-learn` – Machine learning modeling and evaluation
