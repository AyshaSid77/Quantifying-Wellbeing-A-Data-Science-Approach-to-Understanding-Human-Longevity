# Predicting Life Expectancy: A Data-Driven Regression Analysis

##  Overview
This project explores how various human development factors influence Life Expectancy at Birth (LEB). Using regression analysis, it models and predicts LEB from socioeconomic indicators such as the Human Development Index (HDI), Gross National Income (GNI), and educational metrics.

## Key Features
- Train-test data split with reproducibility
-  Single-variable regression using HDI
  - Non-linear transformation for GNI using log scale
- Multi-variable regression with schooling and median age
- Model evaluation using R², MSE, and correlation coefficients
- Visualizations with scatter plots and regression lines

## Tools & Libraries
- Python  
- Pandas, NumPy  
- scikit-learn  
- Matplotlib, Seaborn  

##  Results
| Model Type | R² Score | MSE | Correlation |
|------------|----------|-----|-------------|
| HDI-only Linear | 0.87 | 11.41 | 0.91 |
| Log(GNI) Transformed | 0.88 | - | 0.89 |
| Multiple Regression | 0.836 | 10.27 | 0.92 |

##  Insights
- HDI is a strong predictor of life expectancy due to its direct inclusion of health and education factors.
- GNI exhibits a non-linear relationship; transformation improves correlation.
- Combining median age and education variables gives a slightly better predictive model.

##  How to Run
1. Clone the repo.
2. Run `notebook.ipynb` or `regression_analysis.py`.
3. Check plots and results for model comparisons.

##  References
- UNDP Human Development Reports
- Our World in Data: Life Expectancy

##  Status
 Completed — A great example of exploratory data science using regression!

