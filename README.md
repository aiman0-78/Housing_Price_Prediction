# Housing Price Prediction (ML Project)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3.0-orange)
![Pandas](https://img.shields.io/badge/Pandas-2.0.3-purple)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-green)

---

## Project Overview
This project predicts **California Housing Prices** using **Regression Models**.  
It compares **Linear Regression** and **Decision Tree Regressor** based on **Mean Squared Error (MSE)** and **R² Score**.  

Developed and tested in **Google Colab**.

---

## Dataset
- **Source:** `sklearn.datasets.fetch_california_housing`  
- **Rows:** ~20,640  
- **Features:** 8 (e.g., `MedInc`, `HouseAge`, `AveRooms`, `Latitude`, `Longitude`)  
- **Target Variable:** `MedHouseValue` (Median House Value in $100,000s)  

---

## Steps Completed

1. **Data Loading**  
   - Loaded dataset from Scikit-learn library.

2. **Data Preprocessing**  
   - Split dataset into **train (80%)** and **test (20%)** sets.  

3. **Model Training**  
   - Trained **Linear Regression**  
   - Trained **Decision Tree Regressor (max_depth=5)**  

4. **Evaluation**  
   - Compared results using **MSE** and **R² Score**.  

5. **Visualization**  
   - Plotted **Predicted vs Actual** values for both models.  
   - Displayed performance comparison table.  

---

## Tech Stack
- **Python**  
- **Google Colab**  
- **Pandas, Numpy**  
- **Matplotlib**  
- **Scikit-learn**  

---

## Model Training & Results

### Linear Regression
- **MSE:** ~0.53  
- **R² Score:** ~0.61  

###  Decision Tree Regressor
- **MSE:** ~0.45  
- **R² Score:** ~0.68  

---

## Comparison Table

| Model              | MSE   | R² Score |
|--------------------|-------|----------|
| Linear Regression  | 0.55  | 0.57     |
| Decision Tree      | 0.52  | 0.59     |

**Decision Tree performed better** (higher R² and lower MSE).

---

## Visualizations
- **Linear Regression Predictions**  
- **Decision Tree Predictions**  

*(Graphs available in notebook execution)*  

---

##  How to Run
Click below to open the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aiman0-78/Housing_Price_Prediction/blob/main/House%20price%20prediction%20(regression)%20project.ipynb)

---

## Next Steps
- Try more models (Random Forest, Gradient Boosting).  
- Perform hyperparameter tuning for better accuracy.  
- Deploy the best model using **Streamlit** or **Flask**.  

---

## Contribution
Feel free to **fork** this repository, improve the project, and submit a **pull request**.  
