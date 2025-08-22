🩺 Hypertension Prediction Model  

This project is a **Machine Learning model** designed to predict the likelihood of **Hypertension (High Blood Pressure)** using patient data.  
It was developed as part of my training with **NTI (National Telecommunication Institute)**.  

---

📊 Project Overview  
- **Goal:** Build a predictive model that helps in early detection of hypertension.  
- **Dataset:** Patient records including features such as:
  - Blood Pressure History  
  - Family History  
  - Exercise Level  
  - Smoking Status  
  - And other health-related attributes  

---

🛠 Steps & Methodology  

🔍 Exploratory Data Analysis (EDA)  
- Data inspection (`info`, `describe`, `value_counts`)  
- Handling duplicates & missing values  
- Correlation heatmap & feature distribution visualizations  

🧹 Data Preprocessing  
- Dropped irrelevant column (*Medication*)  
- Label encoding categorical features (BP History, Family History, Exercise Level, Smoking Status)  
- Converted target variable (*Has_Hypertension*) into numeric (Yes → 1, No → 0)  
- Removed outliers using **IQR method**  

🤖 Modeling  
Implemented and compared multiple ML algorithms:  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- KNN  
- SVM  
- XGBoost  

📈 Evaluation  
- Used **Accuracy, MSE, MAE** and other metrics  
- Compared performance across models to identify the best-performing algorithm  

---

💡 Key Insights  
- Machine Learning can support **healthcare decision-making** by providing predictive insights  
- Models like **Random Forest and XGBoost** tend to perform strongly on this dataset  
- Preprocessing (especially encoding and handling outliers) significantly improved performance  

---
