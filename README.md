# 🚀 Project Showcase: Sales Forecasting & Business Insights for a Retail Store
<img width="280" height="350" alt="Infographic Image for Sales Forecasting Project" src="https://github.com/user-attachments/assets/34e7e710-d61d-47fe-990a-f9250cccfba4" />


I recently completed a Sales Forecasting Project where I applied end-to-end Data Analysis & Machine Learning techniques to analyze 420K+ retail transactions and forecast weekly sales across multiple stores and departments.

## 🔹 Data Preparation & Cleaning

### ● Merged datasets: train.csv, features.csv, stores.csv into one consolidated dataset of 421,570 rows & 16 columns.
### ● Converted Date to datetime format for time-series analysis.
### ● Removed highly missing columns (MarkDown1–5 with 60%+ null values).
### ● Handled outliers using the IQR method to cap extreme values.
### ● Encoded categorical features: OneHotEncoding for Store Type (A, B, C) and LabelEncoding for Holiday flag.

## 🔹 Exploratory Data Analysis (EDA)

### ● Distribution of Weekly Sales → Right-skewed with occasional extreme highs.
### ● Sales Trend Over Time → Strong seasonal spikes, especially during holiday weeks.
### ● Sales by Store → Top 10 stores contributed disproportionately to overall sales (Pareto effect).
### ● Sales by Department → Certain departments (e.g., groceries) consistently dominated sales.
### ● Holiday vs Non-Holiday Sales → Holiday weeks had significantly higher average sales.
### ● Monthly Trends → November–December showed sharp peaks across all years.
### ● Sales by Store Type → Type A (large stores) outperformed Type B and C in average weekly sales.
### ● Fuel Price Impact → Higher fuel prices slightly reduced sales.
### ● Unemployment Impact → Higher unemployment correlated with lower sales.
### ● CPI Impact → Inflation trends showed moderate influence on sales.
### ● Top 10 Stores Contribution → Major share of revenue driven by few stores.
### ● Heatmap Analysis → Lag features and rolling averages had the strongest correlation with Weekly Sales.

## 🔹 Feature Engineering

### ● Created time features: Year, Month.
### ● Generated Lag features: Lag1, Lag2.
### ● Created Rolling Averages (3-week rolling mean).
### ● Encoded categorical variables (Store Type, IsHoliday).
### ● Scaled numerical features using StandardScaler.

## 🔹 Model Building

### ● Linear Regression → R² = 97.4%, RMSE ≈ 2335.94
### ● Random Forest Regressor → R² = 98.0%, RMSE ≈ 2044.49
### ● XGBoost Regressor → R² = 98.2%, RMSE ≈ 1931.89 (Best Performing Model)

## 🔹 Feature Importance (Key Drivers of Sales)

### ● Lag1 & RollingMean3 → Past sales strongly predict future sales.
### ● Month & Holiday Indicator → Seasonal and holiday effects were critical.
### ● Department & Store Size → Structural business factors influenced revenue.
### ● Fuel Price, CPI, Unemployment → External macroeconomic indicators had smaller but notable effects.

## 🔹 Business Recommendations

### ● Increase inventory & marketing efforts during holiday seasons to maximize uplift.
### ● Focus on top 10 stores & top-performing departments for strategic growth.
### ● Optimize category-level planning for departments with consistent high sales.
### ● Monitor fuel price, CPI & unemployment for macroeconomic impacts.
### ● Use XGBoost as the production model for accurate and reliable sales forecasting.

## 💡 Key Takeaway:

This project demonstrated how Machine Learning + Data Analytics can deliver actionable insights for retail, enabling smarter inventory planning, better holiday promotions, and data-driven decision-making.

## 🛠 Tools & Technologies:

## Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | XGBoost | Jupyter Notebook

## 💼 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue)](https://www.linkedin.com/in/saumyasuteshnu-behera-50a478209/)
