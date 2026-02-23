# Household Size Prediction from Amazon Purchases

Overview:

This R-based project predicts household size from Amazon purchase data, standardizing products into 8 categories and engineering 52 features like temporal patterns and interactions. Top 21 features are selected via XGBoost importance, with tuned XGBoost achieving RMSE 1.04-5% better than Random Forest, LASSO, and Ridge.
​

Key Findings:

XGBoost excels due to interaction handling; feature selection reduces complexity without performance loss. Standardized categories reveal purchase-household links effectively.
