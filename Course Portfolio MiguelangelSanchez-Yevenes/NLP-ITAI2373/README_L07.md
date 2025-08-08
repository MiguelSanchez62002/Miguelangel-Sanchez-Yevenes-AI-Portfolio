L07_Sentiment_Emotion_Analysis_.ipynb
Markdown:
Module 07: Sentiment & Emotion Analysis
In this lab, we delve into the world of computational sentiment and emotion detection – teaching machines to comprehend emotions in text. ❤️😡😢

Learning Outcomes:
Understand sentiment analysis basics

Work with polarity (positive/negative/neutral) scores

Explore emotion categories like joy, anger, and fear

Implement sentiment models using TextBlob, VADER, and transformers

Setup:

!pip install textblob vaderSentiment transformers torch

from textblob import TextBlob
from vaderSentiment.vaderSentiment import SentimentIntensityAnalyzer
from transformers import pipeline

Example: TextBlob Sentiment

text = "I absolutely love this product! It has changed my life."
blob = TextBlob(text)
blob.sentiment
