# House_price_project


A machine learning project that predicts house prices based on various features such as area, number of rooms, location, and more.  
---

## 🚀 Features
- Predicts house prices based on user input.    
- Data preprocessing (imputation, encoding, scaling) to ensure model accuracy.  
- Trained using **Scikit-learn** and **XGBoost**.  
- Fixed data leakage and improved performance through feature engineering.  

---

## 🧰 Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib  
- **Dataset:** [Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

---

## 🧠 Model Building Steps
1. **Data Cleaning:**  
   - Handled missing values using mean/median imputation.  
   - Removed duplicate or irrelevant entries.  

2. **Feature Engineering:**  
   - Created new features like `TotalSF = GrLivArea + TotalBsmtSF + 2ndFlrSF`.  
   - Encoded categorical columns using one-hot encoding.  

3. **Model Training:**  
   - Trained multiple regression models and tuned hyperparameters.  
   - Selected **XGBoost** for best performance.  

4. **Evaluation:**  
   - Validation RMSE: **0.1516**  
   - Cross-validated RMSE: **0.1340**

---

## 🖥 GUI Overview
The GUI allows users to:
- Input house details (e.g., area, rooms, location).  
- Click **“Predict Price”** to view the estimated price instantly.  

