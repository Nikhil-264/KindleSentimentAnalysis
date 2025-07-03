# Kindle Review Sentiment Analysis 📚💬

A sentiment analysis project on Amazon Kindle book reviews using:
- Text preprocessing with NLTK
- TF-IDF and Word2Vec embeddings
- Naive Bayes and Logistic Regression
- Model saved with Joblib for future inference

## Files
- `Kindle_Review_Sentiment.ipynb` — Main analysis notebook
- `all_kindle_review.csv` — Dataset
- `sentiment_model.pkl` — Saved model for prediction

## Usage
```python
import joblib
pipeline = joblib.load("sentiment_model.pkl")
pipeline.predict(["I hated the book. Waste of time."])
