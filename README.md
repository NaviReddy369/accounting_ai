# Accounting_ai
Forecasting Earnings with AI
Project Overview
This project leverages AI to forecast earnings, specifically focusing on predicting future total assets using historical data from 2010 to 2023. Utilizing the SP500_Restatement.csv dataset, this study employs Linear Regression, Random Forest, and Gradient Boosting models to analyze and predict financial trends and outcomes.

Motivation
The ability to forecast financial outcomes is crucial for investors, accountants, and regulators to make informed decisions. By analyzing the relationship between time and total assets, this project aims to provide a robust methodology for predicting future earnings.

Data and Models
Data Source: SP500_Restatement.csv
Features:
at_change - Change in total assets
fyear - Fiscal year
restatement - Binary flag indicating financial restatements
Models:
Linear Regression
Random Forest
Gradient Boosting
Results
The models demonstrate varying levels of accuracy:

Gradient Boosting Model showed the highest predictive accuracy with a Mean Squared Error (MSE) of 28,935,344,047.06 and an R² Score of 0.409.
Random Forest Model and Linear Regression Model also provided valuable insights, with Random Forest notably improving upon the Linear Regression baseline.
Visual Analysis
Graphs in the appendix illustrate the actual vs. predicted earnings across all models, aiding in performance comparison and reliability assessment.

Conclusion
The Gradient Boosting Model excels in forecasting earnings with high accuracy and substantial relevance of input features. This analysis highlights the importance of selecting appropriate features and models to achieve reliable and actionable insights in financial forecasting.

Future Directions
Future enhancements might include exploring more complex models or incorporating additional features to further improve the accuracy of predictions.
