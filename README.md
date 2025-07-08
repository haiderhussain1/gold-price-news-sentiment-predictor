# Gold Price News Sentiment Predictor

This project predicts gold prices using historical market data and news sentiment.

---

## How to Use

1. Clone the repo:

```bash
git clone https://github.com/yourusername/gold-price-news-sentiment-predictor.git
cd gold-price-news-sentiment-predictor

2. Create and activate a virtual environment:

python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

3. Install packages 
pip install -r requirements.txt

4. Open gold_price_news_sentiment_predictor.py and replace:

NEWS_API_KEY = "4d65f86475074aed8bd21bfb63acc76d"

with your own NewsAPI key.

5. Run the script:

python gold_price_news_sentiment_predictor.py --model xgb

What the script does 

Downloads gold price data and news headlines

Analyses news sentiment
Calculates technical indicators
Trains a machine learning model
Saves predictions and a plot of predicted vs actual prices

Results

RMSE: About 25 USD
R² score: About 0.91 (good fit)

About Me

Mohammed Haider Hussain
GitHub
LinkedIn
