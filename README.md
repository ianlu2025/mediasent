# mediasent
This code uses VADER sentiment metrics to evaluate its impact on IPO performance in the UK between 2021 and 2024

Final_Sentiment_Analysis: Extracts sentiment metrics using the VADER model from IPO-related media articles (pre- and post-IPO). Outputs structured sentiment variables for later analysis.

Final_Full_Data_Preperation: Merges sentiment data with company fundamentals, ownership data, and IPO pricing data into a final dataset. Handles missing data and feature engineering.

Final_Regression_FirstDay: Runs regression models to analyze the relationship between pre-IPO sentiment and first-day stock returns. Includes diagnostics and control variables.

Final_Regression_FirstMonths: Analyzes the impact of post-IPO sentiment on first-month stock returns. Focuses on longer-term sentiment signals and delayed market reaction.

df_final_2: Final cleaned dataset used as input for regression analysis. Contains sentiment, IPO pricing, ownership, and control variables.

df_results: Contains regression outputs and coefficients used for visualizations and reporting in the thesis.

variables: Variable documentation file listing all dataset columns with descriptions and expected value ranges. Useful for replication or peer review.
