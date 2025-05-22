# House-price-prediction(USA)-

🏡 House Price Prediction with XGBoost
This project is a machine learning pipeline for predicting house prices using structured real estate data. The workflow includes data preprocessing, correlation analysis, outlier removal, label encoding, and model training with the powerful XGBoost algorithm. The final model achieved an impressive R² score of 75.35%, indicating strong predictive performance.

📊 Features
📦 Clean and preprocess real estate data

📈 Analyze feature correlations with price

🚫 Remove outliers using IQR method

🏷️ Encode categorical data using LabelEncoder

⚙️ Train a regression model using XGBoost

📉 Evaluate model performance with R² score

🧠 Technologies Used
Python

Pandas

Scikit-learn

XGBoost

Matplotlib / Seaborn

🔍 Data Overview
Key features used in prediction include:

bedrooms, bathrooms, sqft_living, sqft_lot

floors, waterfront, view, condition, grade

city, statezip, yr_built, yr_renovated

Encoded categorical features such as city and statezip

Target variable:

price

📈 Model Performance
Metric	Value
R² Score	75.35%

This R² score indicates that the model explains over 75% of the variance in house prices, which is a solid performance for real estate price estimation.
