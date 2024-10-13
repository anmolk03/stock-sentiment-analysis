# Stock Movement Analysis Based on Social Media Sentiment

## Objective
Analyze and predict stock movements by extracting and analyzing social media data.

## Technologies Used
- Python
- PRAW (for Reddit data)
- Pandas (for data manipulation)
- Matplotlib (for visualization)
- TextBlob (for sentiment analysis)
- yfinance (for stock data)

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/anmolk03/stock-sentiment-analysis.git
   cd stock-sentiment-analysis

2. Install the required packages:
bash

pip install praw pandas matplotlib textblob yfinance


3.Add your Reddit API credentials to the script.

  reddit = praw.Reddit(
    client_id='YOUR_CLIENT_ID',
    client_secret='YOUR_CLIENT_SECRET',
    user_agent='YOUR_USER_AGENT'
)


4. Run the script:
  bash

   sentiment_analysis.py


Data

The script collects data from specific Reddit subreddits related to stocks and fetches historical stock prices for Apple.


Results

The analysis includes sentiment scores correlated with stock prices and visualizations of sentiment trends over time.

Sentiment Analysis: The average sentiment scores were calculated and plotted against the stock prices.

Correlations: The correlation between sentiment and stock price movements was analyzed.


Report Findings

Stocks with high positive sentiment generally showed increased prices over time.

Negative sentiment correlated with price drops, indicating potential sell signals.


Recommendations

It shows a strong correlation between negative sentiment and price drops; traders should proceed with caution.

Consider monitoring social media sentiment regularly as it can provide early indicators of market trends.

Integrate data from multiple sources (e.g., news articles) to enhance prediction accuracy.

Experiment with advanced sentiment analysis techniques or machine learning models for better predictions.


Future Improvements

Integrate more data sources (e.g., news articles).

Use advanced sentiment analysis techniques or machine learning models.
