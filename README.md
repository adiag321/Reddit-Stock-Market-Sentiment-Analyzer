# <p align = 'center'>Reddit Stock Market Sentiment Analyzer</p>

This project analyzes Reddit sentiment to predict stock market trends. It uses natural language processing to analyze Reddit posts and comments about stocks, and correlates this sentiment with actual stock price movements.

## Setup

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

2. Create a `.env` file with your Reddit API credentials:
```
REDDIT_CLIENT_ID=your_client_id
REDDIT_CLIENT_SECRET=your_client_secret
REDDIT_USER_AGENT=your_user_agent
```
To get the credentials, visit <a href = 'https://www.reddit.com/prefs/apps/'>Reddit app preferences</a>. Here,
* your_client_id → is the client ID from Reddit app preferences
* your_client_secret → is the secret key shown there
* your_user_agent → you create it yourself as a string describing your script

3. Run the main script:
```bash
python stock_sentiment.py
```

## Features

- Fetches Reddit posts and comments about specific stocks
- Analyzes sentiment using natural language processing
- Correlates sentiment with stock price movements
- Provides basic trend predictions