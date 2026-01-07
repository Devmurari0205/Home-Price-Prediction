# 🏠 Home Price Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting house prices using machine learning techniques.  
The dataset contains property-related features such as number of rooms, location, distance from CBD, land size, building area, and other relevant attributes.

The goal is to build an accurate regression model by performing proper data preprocessing, feature engineering, and model evaluation.

---

## 📂 Dataset Information
- **Source**: CSV File
- **Target Variable**: `Price`
- **Type**: Regression Problem
- **Region**: Australia (Housing Market)

---

## 🧾 Business Problem
Real estate companies need a reliable way to estimate house prices based on property features.  
This project helps stakeholders:
- Understand key price-influencing factors
- Predict house prices accurately
- Reduce manual valuation effort

---

## 📊 Project Workflow

### 1️⃣ Data Exploration & Preprocessing
- Loaded dataset and explored structure
- Handled missing values
- Dropped irrelevant columns
- Encoded categorical variables
- Created dummy variables
- Cleaned and prepared data for modeling

### 2️⃣ Model Building
- Split data into training and testing sets
- Built **Linear Regression** model
- Checked model performance
- Applied **Ridge** and **Lasso Regression** to handle overfitting

### 3️⃣ Model Evaluation
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Model coefficient analysis

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 📈 Key Insights
- Distance from CBD significantly impacts house price
- Property size and number of rooms are strong predictors
- Regularization improves model generalization

---

## 📁 Folder Description

| Folder | Description |
|------|-------------|
| data/ | Raw and cleaned datasets |
| docs/ | Business requirement and data description |
| notebooks/ | Jupyter Notebook with full analysis |
| reports/ | EDA and model evaluation reports |
| src/ | Python scripts for modular code |

---

## 🚀 How to Run the Project
1. Clone the repository  
2. Install required libraries  
   ```bash
   pip install -r requirements.txt

 👤 Author
-Harsh Devmurari
-Aspiring Data Analyst | Python | SQL | Machine Learning
