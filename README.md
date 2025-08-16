🍷 Red Wine Quality Analysis (UCI ML Repository)

📌 Project Overview

This project analyzes the Red Wine Quality dataset from the UCI Machine Learning Repository. The goal is to explore the chemical properties of red wine, identify the features most correlated with wine quality, and build predictive models.

The project covers:
	•	Exploratory Data Analysis (EDA) to uncover patterns
	•	Feature Engineering for improved modeling
	•	Regression models to predict quality scores
	•	Model Interpretability for real-world insights


🎯 Objectives
	•	Understand how physicochemical properties influence wine quality.
	•	Build regression models to predict wine quality (0–10).
	•	Compare model performance (Linear Regression, Random Forest, XGBoost).
	•	Interpret model results with explainability tools (SHAP).


📂 Dataset Details
	•	Source: UCI Machine Learning Repository
	•	Authors: Paulo Cortez et al., University of Minho, Portugal
	•	Observations: 1,599 red wines
	•	Features: 11 physicochemical properties (e.g., acidity, sugar, sulphates, alcohol)
	•	Target Variable: quality (wine quality score, 0–10, by wine experts)


🧭 Workflow

1. Data Preprocessing
	•	Check nulls & data types
	•	Outlier detection & handling
	•	Scaling numeric features

2. EDA
	•	Distribution of quality scores
	•	Correlation heatmap between features & target
	•	Pairplots (e.g., alcohol vs. quality)
	•	Boxplots of features across quality categories

3. Feature Engineering
	•	Convert quality scores into categories (Low, Medium, High)
	•	Feature interactions (alcohol × acidity)
	•	Standardization & normalization

4. Modeling
	•	Train/test split
	•	Linear Regression as baseline
	•	Random Forest & XGBoost for non-linear patterns
	•	Evaluation Metrics: RMSE, MAE, R²

5. Model Interpretation
	•	Feature importances (tree-based models)
	•	SHAP values → interpret what drives quality



📊 Key Insights
	•	Alcohol is the strongest predictor of wine quality.
	•	Wines with low volatile acidity and higher sulphates tend to score higher.
	•	Ensemble methods (Random Forest, XGBoost) capture non-linear patterns better than linear models.



⚙️ Tools & Libraries
	•	Python 3.12
	•	pandas, numpy
	•	matplotlib, seaborn
	•	scikit-learn
	•	XGBoost
	•	SHAP



📈 Results (Example)
	•	Linear Regression R²: ~0.20
	•	Random Forest R²: ~0.58
	•	XGBoost R²: ~0.64
	•	Top predictors: alcohol, volatile acidity, sulphates
