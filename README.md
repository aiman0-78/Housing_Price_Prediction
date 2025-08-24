
# Titanic Survival Prediction (ML Project)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24.2-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.5.3-purple)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-green)

---

##  Project Overview
This project predicts whether a passenger **survived the Titanic disaster** using machine learning.  
It covers **data cleaning**, **feature encoding**, **exploratory data analysis**, and **ML model training**.  

Developed and tested in **Google Colab** for easy reproducibility.

---

## Dataset
- **Source:** Seaborn’s built-in Titanic dataset  
- **Rows:** 891  
- **Columns:** 15  
- **Target Variable:** `survived` (0 = did not survive, 1 = survived)

---

## Steps Completed

1. **Data Loading**  
   - Loaded Titanic dataset using Seaborn.

2. **Data Cleaning**  
   - Filled missing `age` with **median**.  
   - Filled missing `embarked` with **mode**.  
   - Dropped `deck` column (too many missing values).  
   - Dropped rows with missing `embark_town`.

3. **Encoding**  
   - Encoded `sex` using **LabelEncoder**.  
   - Encoded `embarked` using **OneHotEncoder**.  

4. **Final Dataset**  
   - Prepared dataset ready for ML model training.

---

## Tech Stack
- **Python**  
- **Google Colab**  
- **Pandas, Numpy**  
- **Seaborn, Matplotlib**  
- **Scikit-learn**

---

## Model Training & Evaluation
- **Model Used:** Logistic Regression  
- **Accuracy:** ~78%  

### Confusion Matrix

| Actual \ Predicted | 0 | 1 |
|--------------------|---|---|
| 0                  | 85 | 24 |
| 1                  | 15 | 54 |

- **Key Features Influencing Survival:**  
  `sex`, `pclass`, `sibsp`, `fare`, `embarked`

---

## Visualizations
- Confusion Matrix Heatmap  
- Feature Importance Bar Chart  

*(See the Colab notebook for full visualizations and step-by-step code.)*

---

## How to Run
Click below to open the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aiman0-78/Titanic-ML-Project/blob/main/titanic_project.ipynb)

---

## Next Steps
- Train additional ML models (Decision Trees, Random Forest, etc.).  
- Compare model accuracy & performance.  
- Deploy the best model as a **web app** (Streamlit/Flask).  

---

## Contribution
Feel free to **fork** this repository, improve the project, and submit a **pull request**.  
