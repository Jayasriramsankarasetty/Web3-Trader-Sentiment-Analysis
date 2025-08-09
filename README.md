Web3 Trader Behavior vs. Market Sentiment Analysis
📂 Assignment Overview
This repository contains a data science project analyzing the relationship between trader behavior on the Hyperliquid platform and the broader market sentiment, as measured by the Fear & Greed Index. The objective is to identify hidden trends in profitability, risk, and volume that could inform smarter trading strategies.

This project was completed as part of the data science assignment for the Web3 Trading Team.

🔹 Standardized Submission Format
The repository follows the required submission structure:

ds_yourname/

notebook_1.ipynb: The primary Google Colab notebook containing all Python code for data loading, cleaning, feature engineering, analysis, and visualization.

csv_files/: Contains all intermediate or processed data files.

outputs/: Contains all visual outputs, including charts and graphs generated from the analysis.

ds_report.pdf: The final summarized report detailing key findings, insights, and potential trading strategies.

README.md: This file, providing setup instructions and an overview of the project.

🚀 Setup & Execution
To replicate this analysis, please follow these steps:

1. Prerequisites:

A Python environment (Google Colab is recommended).

The following Python libraries installed: pandas, numpy, matplotlib, seaborn.

2. Data:

Download the two required datasets:

Historical Trader Data: historical_data.csv

Fear & Greed Index: fear_greed_index.csv

Place both CSV files in the same root directory as the notebook_1.ipynb file.

3. Running the Analysis:

Open notebook_1.ipynb in Google Colab or a local Jupyter environment.

Run the cells sequentially from top to bottom.

The script will automatically create the ds_gemini/ directory and save all processed data and visual outputs into the appropriate csv_files/ and outputs/ subfolders.

💡 Summary of Key Findings
The analysis revealed several critical insights into trader behavior:

Extreme Sentiment Amplifies Risk: While the median trader's performance is close to breakeven across all sentiment phases, periods of Extreme Fear or Extreme Greed significantly increase the potential for both very large profits and substantial losses.

Trade Size and Profitability: There is a noticeable trend where larger trade sizes are associated with a slightly higher average profit, suggesting that higher conviction or better capitalization may be a factor in successful trading.

Actionable Insight: The findings support the development of a dynamic risk management strategy. A model could adjust position sizes based on market sentiment—maintaining standard sizes during neutral periods and reducing them during periods of extreme sentiment to mitigate the risk of large drawdowns.

For a more detailed explanation, please refer to the ds_report.pdf file.
