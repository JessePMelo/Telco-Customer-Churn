CRISP-DM Framework

1. Business Understanding
Business problem: A telecommunications company with a high contract cancellation rate (churn).

Objective: Identify the main factors that influence customer churn and predict the probability of cancellation.

Main KPI: Churn rate (%)

Success criteria:
- Classify customers into risk categories (high, medium, low)
- Identify high-value customers with a high probability of churn
- Extract insights about the most relevant variables influencing churn


2. Data Understanding
Data sources: Public dataset provided by IBM

Target variable: Churn

Data period: Not specified

Limitations:
- Lack of geolocation data
- Non-temporal dataset (does not allow time-based analysis)
- Possible synthetic nature of the data


3. Data Preparation
Pipeline:
problem definition → data understanding → data cleaning → feature engineering → modeling → model evaluation → model explainability → model selection → conclusion


4. Modeling
Baseline: Logistic Regression

Candidate models:
- Random Forest
- XGBoost


5. Evaluation
Metrics:
- Precision: 0.52
- Recall: 0.80
- F1-score: 0.63


6. Conclusion
The model showed good performance in identifying customers at risk of churn, with a strong emphasis on recall.

This indicates that the model is effective at capturing customers who are likely to churn, making it useful for retention strategies, despite the trade-off in precision.