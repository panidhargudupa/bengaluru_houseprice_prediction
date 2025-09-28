# 🏠 Bengaluru House Price Prediction

A Python-based data analytics project to **estimate and forecast residential property prices** in Bengaluru using historical housing data and basic analytics.  

This project demonstrates **data cleaning, feature engineering, price per square foot calculation, location-based analysis**, and a simple **future price projection** using a compound growth formula.

---

## 📌 Project Motivation
Bengaluru’s real estate market is **dynamic and location-sensitive**.  
This project helps **home buyers, investors, and developers** quickly estimate fair property prices and forecast price trends by analyzing actual transaction data.

---

## ✨ Features
- ✅ Cleans and preprocesses raw housing datasets  
- ✅ Extracts and engineers features (BHK, sqft conversion, price per sqft, handling missing values)  
- ✅ Location & year-based price lookup  
- ✅ Simple future price prediction (2025–2030) using **6% compound growth**  
- ✅ Interactive analysis & visualization (bar charts, line graphs, distribution plots)  
- ✅ Quick input queries for custom property specifications  

---

## 🔄 Workflow
1. **Data Loading** – Reads housing dataset (`Bengaluru_House_Data_With_Year.xlsx`) from 2011–2024  
2. **Cleaning** – Removes missing/invalid rows, normalizes numeric columns  
3. **Feature Engineering** – Converts BHK/size strings, handles sqft ranges/errors  
4. **Analysis** – Computes price per sqft & aggregates location/year statistics  
5. **Prediction** – Uses latest year price + 6% growth for 2025–2030 forecasts  
6. **Visualization** – Plots market trends & feature distributions  

---

## ⚠️ Limitations
- ❌ No machine learning models (only rule-based formulas)  
- ❌ Static 6% growth rate for forecasting  
- ❌ No advanced input validation for unstructured queries  

---

## 🚀 Usage
1. Open the Jupyter Notebook: `bengaluru_houseprice_prediction.ipynb`  
2. Run all cells step by step  
3. Replace location in query functions with your desired area (e.g., `"Whitefield"`)  
4. Input property details to get estimated prices and trends  
5. Use visualization cells to analyze market patterns  

---

## 🔮 Future Enhancements
- 📊 Integrate **Machine Learning** models (Linear Regression, Random Forest, XGBoost)  
- ⚙️ Automated feature engineering (encoding, scaling, feature selection)  
- 📏 Add model evaluation (train/test split, RMSE/MAE reporting)  
- 🌐 Deploy as a **web application** (Flask, Django, Streamlit)  
- 🔌 Build REST API for real-time price queries  
- 🧾 Add feature importance for explainability  
- 📖 Improve documentation with screenshots and usage guides  

---

## 📂 How to Run
# Clone this repository
git clone https://github.com/panidhargudupa/bengaluru_houseprice_prediction.git

# Place dataset inside project folder
Bengaluru_House_Data_With_Year.xlsx

# Open Jupyter Notebook
jupyter notebook bengaluru_houseprice_prediction.ipynb
