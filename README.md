# Regression_evaluation
All resources of masters thesis: Supervised Learning in Business: Evaluating and Explaining Regression-Based Methods for Pattern Discovery.

This GitHub repository serves as a medium to maintain the identity, reproducibility, and transparency of the results produced in my master's thesis. The research focuses on evaluating the performance and interpretability of supervised regression models applied to financial KPI data from S&P 500 companies.
Four regression-based supervised machine learning models were analyzed:
•	Linear Regression
•	Ridge Regression
•	Lasso Regression
•	Polynomial Regression

Repository Contents:

Tanmay_Ubhate_400338253_Master_Thesis.pdf- Full written thesis with detailed methodology, results, and interpretations
regression_analysis.ipynb- Python Jupyter Notebook implementing the complete regression pipeline
financial data sp500 companies.csv- Raw financial dataset obtained from Kaggle, originally scraped from Yahoo Finance
Figures_Tables- All plots and visual outputs used in the thesis for interpretability and analysis

Setup & Requirements: To replicate results, use Google Colab or any Python IDE with Python 3.7 or higher.
Required Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

This project follows the CRISP-DM pipeline combined with human-in-the-loop judgment:
1.	Data Understanding – Exploratory analysis and identifying patterns
2.	Preprocessing – Handling missing values, outliers, and skewness
3.	Feature Engineering – Selection based on business logic and correlation pruning
4.	Data Splitting and Scaling – Train-test split (70/30) and Z-score normalization
5.	Modelling – Application of regression models using scikit-learn
6.	Evaluation – Metrics include R², MAE, RMSE
7.	Interpretation – SHAP values used to explain feature contributions and support managerial decision-making
   
This project in brief explains, how financial KPIs can be modelled and interpreted using supervised learning to improve decision-making in corporate finance. The pipeline emphasizes interpretability, accuracy, and strategic relevance by combining statistical modelling with domain expertise.
