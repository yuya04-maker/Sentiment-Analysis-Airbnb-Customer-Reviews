# Sentiment Analysis of Airbnb Customer Reviews

## Overview
This project applies Natural Language Processing (NLP) and Machine Learning to analyze customer sentiment from airbnb reviews. The goal is to classify reviews as positive, negative, or neutral based on textual data and extract meaningful insights to improve customer experience.

## Tools & Technologies
- Python
- Pandas, NumPy
- NLTK (text preprocessing, stopwords, tokenization, lemmatization)
- VADER (sentiment analysis)
- Scikit-learn (Naive Bayes, TF-IDF)
- Matplotlib, Seaborn
- WordCloud

## Project Workflow
1. Data cleaning and preprocessing (lowercasing, removing punctuation, stopwords, lemmatization)
2. Sentiment labeling using VADER
3. Text vectorization using TF-IDF
4. Model training using Naive Bayes
5. Model evaluation using accuracy, precision, recall, and F1-score
6. Visualization (word clouds, frequency plots)

## Key Insights
- Most reviews are positive, indicating generally high customer satisfaction
- Words like "great", "clean", and "friendly" are strongly associated with positive sentiment
- Negative reviews frequently mention issues related to "room", "service", and "time"
- Some mismatches exist between ratings and text sentiment, showing that text provides deeper insight than numeric ratings alone

## Model Performance
- Accuracy: 94.5%
- Precision: 94.5%
- Recall: 94.5%
- F1-Score: 92.0%

The model performs well overall but struggles with minority classes (neutral and negative), indicating class imbalance in the dataset.

## Visualizations
- Word clouds for positive and negative reviews
- Top 10 most frequent words
- Distribution of ratings

## Business Recommendations
- Improve consistency in room quality and service speed, as these appear in negative feedback
- Leverage positive feedback themes (cleanliness, staff friendliness) in marketing
- Monitor text-based sentiment alongside ratings for more accurate customer insights

## Files
- Jupyter Notebook with full analysis
- Dataset (TripAdvisor hotel reviews)
