# 📱 Apple Product Pricing Analysis & Rating Prediction

A complete Data Analytics and Machine Learning project that explores Apple product pricing data, performs data preprocessing, feature engineering, exploratory data analysis (EDA), and builds regression models to predict product ratings.

---

## 📌 Project Overview

This project analyzes an Apple product pricing dataset containing information about product categories, launch prices, current prices, discounts, customer reviews, ratings, stock status, and sales events.

The project follows the complete data science workflow:

- Data Understanding
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Feature Scaling
- Model Building
- Model Evaluation

---

## 🎯 Objectives

- Understand pricing patterns across Apple products.
- Analyze customer ratings and review trends.
- Handle missing values, duplicates, and outliers.
- Encode categorical variables.
- Detect multicollinearity.
- Build machine learning models for rating prediction.
- Compare model performance using multiple regression algorithms.

---

## 📂 Dataset Features

The dataset includes information such as:

- Date
- Platform
- Product Category
- Model Name
- Launch Price (USD & INR)
- Current Price (USD & INR)
- Discount Percentage
- Rating
- Reviews Count
- Condition
- Stock Status
- Sale Event

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Statsmodels

---

## 📊 Exploratory Data Analysis

Performed comprehensive EDA including:

- Dataset overview
- Data types inspection
- Statistical summary
- Missing value analysis
- Duplicate detection
- Univariate Analysis
- Bivariate Analysis
- Correlation analysis
- Price distribution
- Rating distribution
- Platform-wise rating comparison
- Product category analysis
- Discount analysis

---

## 🧹 Data Preprocessing

The preprocessing pipeline includes:

- Handling missing values
- Removing unnecessary columns
- Duplicate checking
- Outlier analysis
- One-Hot Encoding for categorical variables
- Date feature extraction
- Feature selection

---

## ⚙ Feature Engineering

Implemented:

- Year extraction from Date
- Correlation Heatmap
- Variance Inflation Factor (VIF)
- Removal of highly correlated features
- Random Forest Feature Importance

---

## 📈 Feature Scaling

Applied:

- RobustScaler

Tree-based models were trained without feature scaling.

---

## 🤖 Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

## 📏 Evaluation Metrics

Models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📁 Project Structure

```
Apple-Pricing-Analysis/
│
├── apple_pricing.ipynb
├── dataset/
│   └── apple_products.csv
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Apple-Pricing-Analysis.git
```

2. Navigate to the project folder

```bash
cd Apple-Pricing-Analysis
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open

```
apple_pricing.ipynb
```

---

## 📌 Key Learning Outcomes

- Exploratory Data Analysis
- Data Cleaning Techniques
- Feature Engineering
- Handling Missing Values
- Outlier Analysis
- Encoding Categorical Variables
- Multicollinearity Detection (VIF)
- Feature Importance
- Feature Scaling
- Regression Modeling
- Model Performance Evaluation

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Interactive dashboard using Streamlit
- Model deployment
- Real-time price prediction API

---

## 👨‍💻 Author

**Sufi Ahamed**

- Python
- SQL
- Data Analysis
- Machine Learning
- Streamlit

---

## ⭐ If you found this project helpful, consider giving it a star!
