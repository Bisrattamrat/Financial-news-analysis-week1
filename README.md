# Financial News Analysis - Week 1

## Project Overview
This project focuses on analyzing financial news headlines and stock market data using Python.

## Tasks Completed
- Exploratory Data Analysis (EDA)
- Sentiment Analysis on financial headlines
- Stock price trend visualization
- Moving Average technical indicator implementation

## Tools & Libraries Used
- pandas
- numpy
- matplotlib
- yfinance
- nltk
- scipy

## Key Findings
- Positive sentiment headlines generally showed higher sentiment scores.
- Apple stock showed an upward trend over the analyzed period.
- The 20-day moving average helped smooth stock price fluctuations.

## Project Structure
- notebooks/ → Jupyter notebooks
- scripts/ → Python scripts
- src/ → Source code
- tests/ → Test files
## Improvements After Feedback

- Added explicit data cleaning steps
- Added duplicate handling
- Added missing value analysis
- Implemented MACD technical indicator
- Improved EDA workflow
- Enhanced notebook organization
## Task 3: Sentiment & Correlation Analysis
The final phase of this project involved measuring the statistical relationship between the "mood" of the news and actual market performance.

* Sentiment Tool: Utilized [TextBlob/VADER] for polarity scoring.
* Metric: Calculated the Pearson Correlation Coefficient between daily news sentiment and stock percentage returns.
* Finding: Discovered a correlation of -0.03. This near-zero value indicates that daily price movements are not linearly dependent on headline sentiment alone.

## Final Investment Recommendations
Based on the integrated analysis of technical indicators and sentiment:
1.  Hybrid Strategy: Investors should use the 20-day SMA to identify the primary trend and use sentiment as a "secondary confirmation" tool.
2.  Volume Sensitivity: News sentiment appears to have a higher impact during periods of high trading volume (e.g., earnings releases).
3.  Long-term vs. Short-term: Daily sentiment acts as "noise"; a more robust strategy should focus on 7-day or 30-day sentiment momentum.

## Repository Contents Update
- output_correlation.png: Scatter plot visualization of Sentiment vs. Returns.
- output_price_sma.png: Visualization of price trends with moving averages.
##Improvements After Feedback
Improved data cleaning (handled missing values, duplicates, and standardized formats)
Enhanced EDA with clearer and more structured visualizations
Added technical indicators (SMA, MACD) for better trend analysis
Improved sentiment analysis and correlation workflow
Reorganized project structure for better readability
Strengthened documentation and results interpretation
## Author
Bisrattamrat
