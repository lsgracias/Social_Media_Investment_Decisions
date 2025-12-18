# Social_Media_Investment_Decisions

I led the NEXIS Finance AI project in Fall 2025, we developed a machine learning system to predict stock investment signals by analyzing social media sentiment and its correlation with market movements. Our team built a model that generates actionable investment recommendations (Invest/Hold/Avoid) based on the sentiment analysis of social media discussions around specific stocks.

## About the Data
The dataset was collected from Kaggle, containing social media posts (primarily from Twitter/Reddit) discussing various stocks, along with corresponding stock price movements over a 7-day period. The data includes:
- Social media text content mentioning stock tickers
- Historical stock price data
- Engagement metrics from social posts
- Temporal data linking posts to price movements

**Data Source:** [Kaggle Stock Market Social Media Dataset](https://www.kaggle.com/datasets/thedevastator/tweet-sentiment-s-impact-on-stock-returns?select=full_dataset-release.csv)

## Model Performance Summary
We utilized **FinBERT** (Financial BERT) for sentiment analysis, a domain-specific language model pre-trained on financial text, to classify social media posts as positive, neutral, or negative. 

### Results Metrics:
* **Sentiment Classification Accuracy:** Successfully classified tweet sentiment with high precision
* **Investment Signal Generation:** Created actionable Invest/Hold/Avoid signals based on sentiment scores
* **Price Movement Correlation:** Identified patterns between social sentiment and 1-7 day price changes
* **Herding Detection:** Model captures market manipulation risks and influencer-driven price movements

### Key Findings:
- Social media sentiment shows strongest correlation with stock prices of smaller companies
- Negative sentiment spreads faster than positive sentiment, causing rapid price fluctuations
- Model successfully identifies "herding behavior" where investors follow trends without research
- System comparable to existing tools like RavenPack and Bloomberg's sentiment analysis

**Insight:** FinBERT effectively captures financial language nuances, providing reliable investment signals while highlighting the risks of social media-driven trading decisions. The model helps investors identify when stock movements are driven by genuine market factors versus social media hype.