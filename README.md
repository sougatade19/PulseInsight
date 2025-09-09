# PRODIGY_DS_04

#  Prodigy Infotech – Data Science Internship (Task 4)

<img src="Prodigy_task_01.png" alt="Banner" style="width:100%; max-width:700px;">

Hi there!   
I'm Sougata, and this repository showcases my submission for **Task 1** of the **Prodigy Infotech Data Science Internship**. In this task, I explored a real-world dataset and used data analysis and visualization techniques to uncover some interesting patterns.

---
# 📊 SentimentScope: Social Pulse Analytics

## 🔍 Project Overview

**SentimentScope** is a sentiment analysis and data visualization project designed to understand public opinion and emotional tone toward specific topics or brands using social media data (e.g., Twitter, Reddit). The project leverages NLP techniques to process user-generated content and reveals trends, moods, and insights that can influence marketing, public relations, or policy decisions.

## 📁 Dataset

We use publicly available datasets or APIs such as:

- [Twitter API](https://developer.twitter.com/)
- [Kaggle - Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140)
- [Reddit Scraped Data](https://www.pushshift.io/)
  
**Sample Columns:**
- `tweet_id`
- `user`
- `timestamp`
- `text`
- `likes`
- `retweets`
- `location` (optional)
- `sentiment_label` (Positive / Neutral / Negative)

## 🧠 Techniques & Tools

- **Data Cleaning**: NLTK, TextBlob, regex, stopword removal, tokenization
- **Sentiment Analysis**: 
  - TextBlob or VADER for rule-based sentiment
  - Fine-tuned BERT for deep learning-based sentiment classification (optional)
- **Visualization**: 
  - Word Clouds
  - Time Series Sentiment Trends
  - Geo-mapping (if location data available)
  - Pie Charts / Bar Graphs for sentiment distribution

## 📈 Sample Visualizations

- Daily/Weekly sentiment trend lines
- Top 10 keywords by sentiment class
- Heatmap of emotions (if using emotion classification like anger, joy, sadness, etc.)

## 🏁 Project Goals

- Understand how users feel about specific hashtags/brands/topics
- Monitor brand reputation and detect sudden sentiment shifts
- Identify influential users or viral posts that shaped public opinion


## Install required packages:



-` pip install -r requirements.txt `


## Run the main script:

- ` python sentiment_analysis.py `

## 📌 Requirements

- Python 3.7+
- pandas
- matplotlib / seaborn / plotly
- nltk
- textblob / vaderSentiment
- tweepy (if using Twitter API)
- scikit-learn (for model training, optional)
- transformers (if using BERT)


## 🤝 Contributing
Pull requests and suggestions are welcome! For major changes, please open an issue first to discuss what you would like to change.

