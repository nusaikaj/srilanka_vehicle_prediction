# 🚗 Sri Lankan Vehicle Price Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict vehicle prices in Sri Lanka using machine learning techniques.  
By analyzing vehicle attributes such as brand, model, year of manufacture, engine capacity, and mileage, the model helps estimate fair market prices for vehicles.

This project is suitable for **data science portfolios**, **internship interviews**, and **machine learning practice**.

---

## 📂 Dataset
- Source: Kaggle – Sri Lankan Vehicle Sales Dataset
- Each record contains:
  - Brand
  - Model
  - Year of Manufacture (YOM)
  - Engine Capacity (cc)
  - Mileage (KM)
  - Fuel Type
  - Gear Type
  - Town
  - Price (Target variable)

---

## 🧹 Data Preprocessing
- Removed unnecessary columns
- Cleaned and standardized column names
- Handled inconsistent spelling in mileage column
- Encoded categorical variables
- Split data into training and testing sets (80/20)

---

## 🤖 Models Used
- **Linear Regression** (Baseline model)
- **Random Forest Regressor** (Improved performance)

---

## 📊 Model Evaluation
The models were evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

The Random Forest model performed significantly better than the baseline Linear Regression model.

---

## 🔍 Feature Importance
Key features influencing vehicle prices:
- Year of Manufacture (YOM)
- Mileage (KM)
- Engine Capacity (cc)
- Brand and Model

---

## 🧠 Key Insights
- Newer vehicles with lower mileage tend to have higher prices
- Engine capacity and brand significantly impact vehicle value
- Machine learning models can assist buyers and sellers in pricing decisions

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Kaggle Notebook

---

## ▶️ How to Run
1. Clone the repository
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
