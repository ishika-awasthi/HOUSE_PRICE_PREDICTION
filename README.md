# 🏠 Housing Price Prediction

This project predicts housing prices using various machine learning models based on features such as area, number of rooms, location, and other key attributes. It demonstrates the complete data science workflow — from data cleaning and feature engineering to model training and evaluation.

---

## 📊 Project Overview
- **Objective:** Predict house prices based on given features  
- **Type:** Regression Problem  
- **Tech Stack:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 📂 Dataset
- **Source:** [Kaggle](https://www.kaggle.com/)
- **Description:**  
  - Each record represents a property with numerical and categorical attributes  
  - **Target variable:** `Price`

---

## 🔍 Workflow
1. **Data Preprocessing**
   - Handle missing values  
   - Encode categorical features  
   - Apply feature scaling and normalization  
2. **Exploratory Data Analysis (EDA)**
   - Distribution plots, correlations, outlier detection  
   - Visualize feature importance  
3. **Model Building**
   - Models tried: Linear Regression, Random Forest, XGBoost  
   - Hyperparameter tuning with GridSearchCV  
4. **Evaluation Metrics**
   - R² Score  
   - Mean Squared Error (MSE)  
   - Mean Absolute Error (MAE)  
5. **Results**
   - Best model: **Random Forest Regressor** *(update if different)*  
   - R² Score: **0.87** *(replace with actual result)*  

---

## 📈 Visualizations
- Predicted vs Actual Prices  
- Feature Importance  
- Error Distribution  

---

## ⚙️ Installation & Usage
```bash
# Clone this repository
git clone https://github.com/<your-username>/House-Price-Prediction.git

# Navigate to the folder
cd House-Price-Prediction

# Install required libraries
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook "House Price Prediction.ipynb"


