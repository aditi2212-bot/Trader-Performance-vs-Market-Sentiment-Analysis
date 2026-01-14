# Trader Behavior Insights Using Market Sentiment

## Objective
The objective of this project is to explore the relationship between trader
performance and market sentiment using historical trading data and the Bitcoin
Fear & Greed Index.

## Datasets Used
 Historical Trader Data (Hyperliquid)
 Bitcoin Fear & Greed Index

## Methodology
 Loaded and cleaned high-frequency trader data
 Converted Unix timestamps to date format
 Merged trader data with market sentiment data based on date
 Performed exploratory analysis to evaluate sentiment-based performance

## Key Observation
The trader dataset contains records from 2024, while the Fear & Greed Index
dataset covers earlier time periods. Due to non-overlapping date ranges,
sentiment values could not be mapped to trader activity. This limitation was
identified during the merging stage and documented transparently.

## Conclusion
Although direct sentiment-based performance analysis was limited due to dataset
misalignment, the project demonstrates a complete data analysis workflow and
highlights the importance of temporal alignment when combining financial and
sentiment datasets.




## Tools Used
Python, Pandas, Matplotlib
