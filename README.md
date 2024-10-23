# Fake News Detector

This repository implements a simple fake news detection program using Python libraries:

- NLTK (Natural Language Toolkit) for text processing

- scikit-learn (sklearn) for machine learning algorithms
## Dataset

The program utilizes a dataset from Kaggle -  https://www.kaggle.com/competitions/fake-news/data?select=train.csv and focuses on news content analysis to identify potentially fake news articles.
## Key Features

Text Preprocessing:
- Removes stop words (common words like "the", "a", "an")
- Applies Porter Stemmer to reduce words to their root form (e.g., "running" -> "run")
Feature Engineering:
- Uses TF-IDF Vectorizer to convert text data into numerical features
Classification:
- Employs Logistic Regression to classify news articles as real or fake based on the extracted features
## Output

- Train accuracy - 0.98
- Test accuracy - 0.97
