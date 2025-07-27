# Sentiment Analysis Project: Emotion Classification using Random Forest

Welcome to my Sentiment Analysis project! This repository contains a complete NLP pipeline that classifies text data into binary emotion categories — identifying positive emotions (love, joy, surprise) vs. other emotions (anger, sadness, fear) — using a Random Forest classifier.

---

## Project Overview

This project aims to build an effective and interpretable model for emotion detection from textual data. Starting from raw text, the workflow covers:

- Data loading and exploration
- Text preprocessing including cleaning, stopword removal, and lemmatization
- Feature extraction via CountVectorizer using unigrams and bigrams
- Model training and hyperparameter tuning with `RandomizedSearchCV` / `GridSearchCV`
- Evaluation on a held-out test set demonstrating strong performance (96.2% accuracy)
- A custom input interface for predicting emotions from user-entered text

---

## Key Features
- **Preprocessing:** Careful cleaning and normalization of text to improve model quality.
- **Lemmatization:** Reducing words to their base form to better generalize.
- **Feature Engineering:** Use of n-gram vectorization for richer textual features.
- **Modeling:** Random Forest, a robust ensemble model, tuned for best performance.
- **Evaluation:** Comprehensive metrics including accuracy, precision, recall, and F1-score.
- **User Interaction:** Simple input function for quick emotion prediction on new text.

---

## Dataset

The dataset used in this project is publicly available from [Kaggle: Emotions Dataset for NLP](https://www.kaggle.com/datasets/praveengovi/emotions-dataset-for-nlp). It consists of labeled text samples with emotion tags and was used for training, validating, and testing the model.

---

## Code Structure and Comments

To make the project accessible and easier to follow, I have added detailed **comments throughout the code**. These comments explain the purpose of each step, the reasoning behind certain choices, and tips for adaptation or extension. Whether you’re new to NLP or machine learning, you should find the logic straightforward to understand and replicate.

---

## How to Use

1. Clone this repository.
2. Install required libraries (`nltk`, `scikit-learn`, `wordcloud`, etc.).
3. Download the Kaggle emotion dataset or use the provided data files.
4. Run the notebook or scripts sequentially to replicate preprocessing, training, and evaluation.
5. Use the included function to input your own text and receive emotion predictions!

---

## Contact and Contributions

Feel free to open issues or pull requests if you find bugs, want to add features, or improve the code.  
I’m happy to connect and collaborate with fellow data scientists and NLP enthusiasts.

---

## License

This project is open-source and available under the MIT License.

---

Happy exploring!  
— Dewansh

[GitHub Profile](https://github.com/Dewansh29?tab=repositories)
