## senetiment_analysis
This repository contains a machine learning project focused on detecting hate speech in tweets. The primary goal is to classify tweets as either containing racist/sexist content or being non-offensive, utilizing various text preprocessing techniques, feature extraction methods, and classification algorithms.

## Methodology
# Data Preprocessing and Cleaning
This crucial phase prepares the raw tweet data for effective model training. It addresses noise, inconsistencies, and irrelevant information. Key steps include:

# Removing Twitter handles: Eliminated @user mentions as they provide little semantic value.

# Cleaning punctuation, numbers, and special characters: Stripped away symbols and non-alphanumeric characters.

# Removing small words: Discarded short, common words that do not add significant meaning.

#Normalization (Stemming): Reduced words to their base form (e.g., 'loves', 'loving' to 'love') using Porter Stemmer to reduce dimensionality and improve consistency.

# Tokenization: Breaking down the text into individual words or "tokens."

## Feature Extraction
After cleaning, the text data was transformed into numerical features suitable for machine learning models using:

## Bag-of-Words (BoW): Represents text as a bag of word occurrences, ignoring grammar and word order.

## TF-IDF (Term Frequency-Inverse Document Frequency): Weights words based on their frequency in a document relative to their frequency across the entire corpus, giving more importance to rare but significant words.

# Model Building
Several machine learning models were trained and evaluated for the classification task:

# Logistic Regression: A linear model used for binary classification.

# Support Vector Machine (SVM): A powerful classification algorithm that finds the optimal hyperplane to separate classes.

# RandomForest: An ensemble learning method that builds multiple decision trees and merges their predictions for improved accuracy and robustness.
