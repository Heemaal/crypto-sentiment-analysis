# crypto-sentiment-analysis
Trader Performance & Sentiment Analysis
Objective

This project analyzes trader performance in relation to market sentiment phases (Fear, Greed, Neutral). The goal is to understand how PnL (Profit & Loss) outcomes vary with sentiment conditions and whether buy-side or sell-side positions perform better under different market moods.

Data

Historical Trading Data (historical_data.csv)

Fear & Greed Index Data (fear_greed_index.csv)

The Fear & Greed index was used to label trading days into different sentiment categories:

Extreme Fear

Fear

Neutral

Greed

Extreme Greed

Methodology

Data Cleaning & Preprocessing

Merged historical trading data with sentiment index values.

Assigned sentiment phases based on index thresholds.

Exploratory Analysis

Examined trade distribution across sentiment categories.

Separated buy-side and sell-side trades for performance comparison.

Profitability Analysis

Calculated average PnL by sentiment phase.

Compared buy vs. sell side profitability.

Identified performance differences under extreme sentiment conditions.

Key Findings

Trader performance varies significantly across sentiment phases, with higher PnL observed during Greed and Extreme Greed phases.

Sell-side trades showed stronger profitability compared to buy-side under most conditions.

Extreme sentiment phases (Extreme Fear / Extreme Greed) correlated with notable changes in trading outcomes, often amplifying gains or losses.

Results

The analysis highlights how market psychology impacts trading performance. This can be used for:

Designing better trading strategies

Timing entries/exits based on sentiment

Understanding risk exposure under extreme sentiment conditions

How to Run

Clone this repository:

git clone https://github.com/your-username/trader-behavior-insights.git


Install required libraries:

pip install pandas matplotlib seaborn


Run the analysis notebook or script.
