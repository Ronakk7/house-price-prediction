# house-price-prediction
# 🏠 House Price Prediction

This project applies data preprocessing, feature engineering, and machine learning techniques to predict house prices using the Ames Housing dataset from Kaggle.

## 📁 Dataset
Dataset Source: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

## 🔧 Steps Involved

1. **Data Cleaning**
   - Dropped columns with more than 40% missing values
   - Filled numeric columns with median values
   - Filled categorical columns with mode values

2. **Feature Engineering**
   - Created new features like total square footage and house age
   - Used one-hot encoding for categorical features

3. **Scaling**
   - Standardized numeric features using `StandardScaler`

4. **Export**
   - Final processed dataset exported as `processed_house_data.csv` for further modeling

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib & Seaborn (for EDA)

