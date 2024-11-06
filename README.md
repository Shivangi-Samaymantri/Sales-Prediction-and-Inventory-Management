# Sales Prediction and Inventory Management

This project aims to predict sales revenue and analyze purchasing patterns to support effective inventory management for e-commerce data. Using machine learning models, it provides actionable insights into customer behavior and optimizes inventory planning based on sales trends.

### Key Objectives
- **Predict Sales Revenue**: Employ machine learning algorithms to accurately forecast revenue based on historical sales data.
- **Understand Customer Patterns**: Analyze customer purchasing behaviors to inform marketing and stock strategies.
- **Optimize Inventory**: Use predictions and trend analysis to manage inventory efficiently, minimizing overstock and stockouts.

### Project Workflow
1. **Data Preprocessing**: The dataset includes details like InvoiceNo, StockCode, Quantity, InvoiceDate, and UnitPrice. Missing values are handled with forward/backward filling, and outliers are identified using IQR analysis.
2. **Exploratory Data Analysis (EDA)**: Visualizations offer insights into data distribution, customer demographics, and product popularity.
3. **Modeling**: Implemented Random Forest and Gradient Boosting Regressors to predict sales revenue. Evaluation metrics include RMSE and R² to measure model performance.
4. **Results & Insights**: Provides recommendations on inventory adjustments and highlights key purchasing trends.

### Tech Stack
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Machine Learning Models**: Random Forest Regressor, Gradient Boosting Regressor

