# SMS Spam Detection

## Overview
This project implements an SMS Spam Detection system using Machine Learning techniques. The model classifies SMS messages as either spam or ham (not spam) based on textual features.

## Features
- Preprocessing of SMS text data (tokenization, stopword removal, and vectorization)
- Machine Learning classification (using algorithms such as Naïve Bayes, SVM, or Random Forest)
- Performance evaluation using accuracy, precision, recall, and F1-score

## Requirements
Make sure you have the following dependencies installed:

```bash
pip install pandas numpy sklearn nltk
```

## Dataset
The dataset used for training and testing contains SMS messages labeled as spam or ham. You can use publicly available datasets such as the `SMSSpamCollection` dataset from the UCI Machine Learning Repository.

## Usage
1. Clone the repository or download the script.
2. Ensure all required dependencies are installed.
3. Run the script:

```bash
python SMS_SPAM_DETECTION.py
```

4. The script will train the model, evaluate performance, and allow testing with sample messages.

## Model Training
- The dataset is split into training and testing sets.
- Text preprocessing includes removing special characters, converting text to lowercase, and applying TF-IDF or CountVectorizer.
- A classification model is trained on the processed data.

## Evaluation Metrics
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

## Future Improvements
- Implement deep learning models such as LSTMs for improved accuracy.
- Deploy the model as a web service using Flask or FastAPI.
- Integrate with messaging applications for real-time spam detection.
